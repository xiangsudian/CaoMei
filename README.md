这里放一个大的草莓图标库的 Logo (??? * 200)

# [草莓图标库](http://x.y/z)

为开发者设计的一套免费开源图标库

- 草莓图标库的特点一
- 草莓图标库的特点二
- 草莓图标库的特点三

这里放上草莓图标库的宣传图 (888 * ???)

## 开始使用

### 获取草莓图标库

这里提供三种方式：

#### 使用在线的 unpkg 版本

TBD

#### 下载后使用

TBD

#### 通过安装 npm 使用

TBD

### 使用方法

TBD

## 开发

草莓图标库使用 [IcoMoon App](https://icomoon.io/#app-features) 构建 css。

### 更新新版本

1. 上传 SVG 格式的图标到 [IcoMoon App](https://icomoon.io/#app-features)
2. 生成之后手动替换掉 `dist` 中的文件
3. 执行 `git add :/ && git commit -m "Update icons"` 提交更新
4. 执行 `npm version patch && git push && npm publish` 提交到 GitHub 和 npm（视更新内容可能需要将 `patch` 替换为 `minor` 或 `major`，详见版本号规则）

### 版本号规则

草莓图标库 will be maintained under the Semantic Versioning guidelines as much as possible. Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

- Breaking backward compatibility bumps the major (and resets the minor and patch)
- New additions, including new icons, without breaking backward compatibility bumps the minor (and resets the patch)
- Bug fixes, changes to brand logos, and misc changes bumps the patch
- For more information on SemVer, please visit http://semver.org.

## License

- 草莓图标库中的字体遵循 [SIL OFL 1.1](http://scripts.sil.org/OFL) 协议
- 草莓图标库中的 css 遵循 [MIT](https://opensource.org/licenses/mit-license.html) 协议
- 草莓图标库中的文档遵循 [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/) 协议
