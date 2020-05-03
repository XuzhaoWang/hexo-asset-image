# hexo-asset-image


Give asset image in hexo a absolutely path automatically

# Usege

```shell
git clone https://github.com/XuzhaoWang/hexo-asset-image.git
# npm install hexo-asset-image --save
# This version is different from the npm.
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
