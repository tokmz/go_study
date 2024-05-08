# git 基本使用

### 检查Git版本

```sh
git --version 
```

### 设置Git config

```sh
git config --global user.name "aikzy"
git config --global user.email "aikzy@qq.com"

git config --global --list
```

### 初始化Git仓库

```sh
git init
```

### 仓库状态

```sh
git status
```

### 添加文件

```sh
# 添加所有文件
git add .
# 添加指定文件
git add example.txt    
```

用于将文件的改动添加到Git的索引区

### 提交命令

```sh
# 提交当期索引区的所有改动
git commit
# 提交并编写提交信息
git commit -m "提交信息"
# 修改最近的提交
git commic --amend
# 交互式的选择要提交的改动
git add -i
# 然后使用 git commit 来完成提交

# 使用交互式命令来选择改动并提交
git commit -o
```

用于将已经通过git add 添加到索引区的改动创建一个新的提交



