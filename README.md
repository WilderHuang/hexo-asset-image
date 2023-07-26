# hexo-asset-image

一个hexo处理图片路径问题的仓库备份，使用的时候，用下面的npm install安装命令安装。

Give asset image in hexo a absolutely path automatically

# Usege

```shell
npm install hexo-asset-image --save
```

# Example

```shell
MacGesture2-Publish
├── apppicker.jpg
├── logo.jpg
└── rules.jpg
MacGesture2-Publish.md
```

Make sure `post_asset_folder: true` in your `_config.yml`.

Just use `![logo](logo.jpg)` to insert `logo.jpg`.

# History

2018-04-18: support hexo-abbrlink
