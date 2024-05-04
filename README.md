### Picgo + Typora 使用教程

在 Typora 中配置：

<img src="https://raw.githubusercontent.com/littlegagaduck/img/main/img/image-20240504151106790.png" alt="image-20240504151106790" style="zoom: 80%;" />

打开配置文件，按照 [链接](https://picgo.github.io/PicGo-Core-Doc/zh/guide/config.html#%E9%BB%98%E8%AE%A4%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6) 中的要求，完成以下格式的配置：

```json
{
  "picBed": {
    "uploader": "github",
    "github": {
      "repo": "", // 仓库名，格式是 username/reponame
      "token": "", // github token
      "path": "img/", // 自定义存储路径，比如 img/
      "customUrl": "", // 自定义域名，注意要加 http://或者 https://
      "branch": "main" // 分支名，默认是 main
    } 
  },
  "picgoPlugins": {} // 为插件预留
}
```

token 的获取参考 [知乎教程](https://zhuanlan.zhihu.com/p/168729465)。

