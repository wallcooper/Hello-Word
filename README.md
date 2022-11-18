# Hello-Word
#### 将gitbash 连接到 github
1. 在本地创建项目文件夹
 ```   
    git init
    git add .
    git commit - m "写点什么"
    git config user.name "xxx"  // 如果要创建多个项目，不要加 --global
    git config user.email "email-address"
    git remote add origin https://github.com/blabla
    git push -u origin master
```