![enter image description here](http://chuangzaoshi.com/icon/caomeibanner.png)

# [草莓图标库](http://chuangzaoshi.com/icon/)

为开发者设计的一套免费开源图标库

- 16X16的像素方格大小精心绘制，像素级别的完美显示
- 资源轻量、使用灵活、多设备兼容
- 原创设计，风格统一，私用商用无版权风险

## 开始使用

### 获取草莓图标库
http://chuangzaoshi.com/icon/

### 使用方法

1. 将整个草莓图标库的目录复制到你的项目中
2. 在 `<head>` 标签中添加 `<link rel="stylesheet" href="path/to/caomei.css">`
3. 在需要图标的地方添加对应 `class` 的 `<span>` 即可，已书籍图标为例，`<span class="czs-book"></span>` 即可

查看所有图标示例请点[这里](http://chuangzaoshi.com/icon/)。

## 开发

草莓图标库使用 [IcoMoon App](https://icomoon.io/#app-features) 构建 css。

### 更新新版本

1. 上传 SVG 格式的图标到 IcoMoon
2. 生成之后手动替换掉 `dist` 中的文件
3. 执行 `git add :/ && git commit -m "Update icons"` 提交更新
4. 执行 `npm version patch && git push && npm publish` 提交到 GitHub 和 npm（视更新内容可能需要将 `patch` 替换为 `minor` 或 `major`，详见版本号规则）

### 版本号规则

草莓图标库遵从语义化版本号规则：

`<主版本号>.<次版本号>.<修订号>`

版本号递增规则如下：

主版本号：当你做了不兼容的 API 修改
次版本号：当你做了向下兼容的功能性新增
修订号：当你做了向下兼容的问题修正

更多请看： http://semver.org/lang/zh-CN/

## License

- 草莓图标库中的字体遵循 [SIL OFL 1.1](http://scripts.sil.org/OFL) 协议
- 草莓图标库中的 css 遵循 [MIT](https://opensource.org/licenses/mit-license.html) 协议
- 草莓图标库中的文档遵循 [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/) 协议

## 品牌图标

草莓图标库中的所有品牌标志均为其各自所有者的商标。
请勿将品牌图标用于除了代表该品牌或服务之外的目的。
