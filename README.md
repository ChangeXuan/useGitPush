# useGitPush
- 在github上新建一个仓库
- 在你想上传的文件上单击右键，选择git bash
- $ git init
- $ git add .
- $ git remote add origin git@github.com:zeroSwift/xxxx.git
- $ touch README (创建一个README文件，这个步骤可省)
- $ git add README (向.git中添加这个README文件，这个步骤可省)
- $ git commit -m 'this is my requests'
- $ git push origin master
