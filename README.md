浏览器主页

贡献代码的方式
`fork`本开源项目到自己的仓库，如`your/BlueWhaleHomePage`，然后`clone`到本地（注意：是`clone`你`fork`后的你的仓库里的项目），并配置用户信息
```bash
$ git clone https://gitee.com/your/DBlog.git
$ cd DBlog
$ git config user.name "your name"
$ git config user.email "your email"
```

本地修改代码后，推送到自己的仓库
```bash
$ git commit -am "change something"
$ git push origin master
```

最后在你仓库里fork的项目里提交Pull Request 即可
