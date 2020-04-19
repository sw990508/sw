### github 创建和上传基础操作

==上传==

1. 先创建仓库 sw    
2. 把项目拷贝下来 

```python
   git clone ‘仓库地址’
```

3. 切换到仓库目录
4. 初始化 
```python
  git init
```
5. 操作你的仓库
6. 添加操作 
```python
  git add .
```
7. 提交操作备注
```python
  git commit -m '备注' 
```
8.提交操作，验证身份
```python
  git push -u origin master
  >账户
  >密码 
```

==删除  github  上部分文件夹== 

 1. 先到仓库目录下 
 2. 删除文件夹r or 文件 f
```python
   git rm -r --cached target 
```

 3. 提交删除注释
```python
   git commit -m '删除了target' 
```

 4. 提交操作 
```python
   git push -u origin master
```


