# image-lit

个人图床

## 如何在 `Github` 搭建个人图床

### 搭建步骤

1. 新建一个 github repo, **设置为 `public` 公开的**
2. 创建一个给图床用的 [`token`](https://github.com/settings/tokens), 复制好保存, 一会给 **PicGo** 用
3. 下载 **PicGo** 图床工具, 这个工具是可以将本地图片上传到github repo上, 下载安装完需要配置些东西

### 配置 PicGo 工具

<img width="800" alt="image" src="https://user-images.githubusercontent.com/24643748/233372365-8111bdf8-aca1-4b47-9592-89e771df79e1.png">

设置项解释:

- 设定仓库名: user/repo-name
- 设定分支名: branch name
- 设定token: 复制第二步的token
- 设定存储路径: 可不设置
- 设定自定义域名: 这个相当于给图片对外访问的地址, 这里我用了 `jsdelivr` cdn 加速访问图片, github 访问较慢

  示例: `https://cdn.jsdelivr.net/gh/MrZhouZh/image-lit/blog/wallhaven-4yy7e7_3840x1600.png`

### 参考资料

- [PicGo 开源图床工具](https://github.com/Molunerfinn/PicGo/releases/)

- CDN 加速访问图片

  - [jsdelivr CDN 加速](https://www.jsdelivr.com/?docs=gh)
  - [statically CDN 加速](https://statically.io/)
