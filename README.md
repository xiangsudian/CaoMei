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
3. 在需要图标的地方添加对应 `class` 的 `<i>` 即可，已书籍图标为例，`<i class="czs-book"></i>` 即可

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

## 草莓1.2.1更新日志
![v1.2.1](http://ww3.sinaimg.cn/large/006HJ39wgy1fho2fkbilfj30q902kjr6.jpg)
- 优化：[control] 
- 新增：[add] [brush] [brush-l] [clothes] [clothes-l] [control-rank [rollerbrush] [rollerbrush-l] [ruler] [ruler-l] [share]

## 草莓1.2.0更新日志
![v1.2.1](http://ww3.sinaimg.cn/large/006HJ39wgy1fhqjsr8yo0j30x607h3yl.jpg)
- 优化：[czs-cup] [czs-cup-l]
- 新增：[czs-clock] [czs-clock-l] [czs-read] [czs-read-l] [czs-calculator] [czs-calculator-l] [czs-bluetooth] [czs-bluetooth-l] [czs-briefcase] [czs-briefcase-l] [czs-coin] [czs-coin-l] [czs-bitcoin] [czs-money] [czs-eye] [czs-code-fork] [czs-code-branch] [czs-quote-left]  手势：[czs-hand-bevel] [czs-hand-slide] [czs-hand-gather] [czs-hande-vertical] [czs-hand-Horizontal] [czs-hand-button] [czs-hand-touch] [czs-hand-pointer] [czs-hand-grasp] [czs-hand-stop] 
- 官网：16px和32px 图标大小视觉切换！

## 草莓1.0.1更新日志
![v1.2.1](http://ww3.sinaimg.cn/large/006HJ39wgy1fho2fkbilfj30q902kjr6.jpg)
- 优化：[chemistry] [chemistry-l] [bug] [message-l] [tmall] [talk] [talk-l] [bilibili] [menu-l] [pengyouquan]
- 新增：[bug-l] [message] [save-l] [camera] [layout-grids] [category-l] [location] [command-l] [command]
- 修复：纠正1.0.0命名错误！
