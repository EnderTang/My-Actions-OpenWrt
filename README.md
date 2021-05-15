# 自动编译OpenWrt
[中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

## 用法
- 单击使用此模板按钮创建一个新的存储库。
- 使用Lean的OpenWrt源代码生成.config文件。 （您可以通过工作流文件中的环境变量来更改它。）
- 将.config文件推送到GitHub存储库。
- 在“操作”页面上选择“构建OpenWrt”。
- 单击运行工作流程按钮。
- 构建完成后，单击“操作”页面右上角的Artifacts按钮以下载二进制文件。

## Usage
- Click the [Use this template](https://github.com/P3TERX/Actions-OpenWrt/generate) button to create a new repository.
- Generate `.config` files using [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) source code. ( You can change it through environment variables in the workflow file. )
- Push `.config` file to the GitHub repository.
- Select `Build OpenWrt` on the Actions page.
- Click the `Run workflow` button.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.
