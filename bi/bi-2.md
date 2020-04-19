== wad : 查看网站技术  == 
```python 
wad -u '域名'
```

== whois : 查看域名所有人信息== 

    whois + 域名

== xpath : 是指类似 正则的 规则 == 

== 获取数据使用 模块 以下 == 

    BeautifulSoup ,  lxml

== 笔记3 正则表达式，python - re 板块 == 

        w = word >>  + : 是指单词 多个 ; \S\s 是指字符串 = 中文

    > search  -- 搜索
        例子： re.search(r'(\w+)(,)', s ) 是指 搜索 一个单词 + ，
    > split   -- 匹配的字符分割
        例子： re.split('\W+',ss) 是指 搜索 分割字符
    > sub and subn(多次)     -- 替换字符
        例子： re.sub(r'(\w+)(,)',‘her‘,'', s)  替换成her
    > compile : 事先编写正则规则
        例子： re.compile(r'(\w+)') 
        百度标题获取 ：
             pt = re.compile(r'(<title>)([\S\s]+)(</title>)')
             print(pt.search(r).group(2)) 
