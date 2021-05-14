# 自动编译OpenWrt
[Read the details in my blog (in Chinese) | 中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

## 用法
单击使用此模板按钮创建一个新的存储库。
使用Lean的OpenWrt源代码生成.config文件。 （您可以通过工作流文件中的环境变量来更改它。）
将.config文件推送到GitHub存储库。
在“操作”页面上选择“构建OpenWrt”。
单击运行工作流程按钮。
构建完成后，单击“操作”页面右上角的Artifacts按钮以下载二进制文件。
## 小点
创建.config文件和构建OpenWrt固件可能需要很长时间。 因此，在创建存储库以构建自己的固件之前，您可以通过在GitHub中搜索Actions-Openwrt来检查其他人是否已经构建了满足您需要的固件。
将您所构建固件的一些元信息（例如固件体系结构和已安装的软件包）添加到存储库简介中，这将节省其他人的时间。

## Usage
- Click the [Use this template](https://github.com/P3TERX/Actions-OpenWrt/generate) button to create a new repository.
- Generate `.config` files using [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) source code. ( You can change it through environment variables in the workflow file. )
- Push `.config` file to the GitHub repository.
- Select `Build OpenWrt` on the Actions page.
- Click the `Run workflow` button.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.
## Tips
- It may take a long time to create a `.config` file and build the OpenWrt firmware. Thus, before create repository to build your own firmware, you may check out if others have already built it which meet your needs by simply [search `Actions-Openwrt` in GitHub](https://github.com/search?q=Actions-openwrt).
- Add some meta info of your built firmware (such as firmware architecture and installed packages) to your repository introduction, this will save others' time.
