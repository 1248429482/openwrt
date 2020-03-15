# Actions-OpenWrt

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)](https://github.com/P3TERX/Actions-OpenWrt/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)](https://github.com/P3TERX/Actions-OpenWrt/fork)

使用github操作构建openwrt

[Read the details in my blog (in Chinese) | 中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

## Usage

- 点击 [Use this template](https://github.com/P3TERX/Actions-OpenWrt/generate) 按钮来创建新的存储库。
- 产生 `.config` 文件使用 [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) 源代码. ( 您可以通过工作流文件中的环境变量进行更改. )
- 推入 `.config` 文件添加到GitHub存储库中，构建会自动开始。进度可以在``操作''页面上查看。
- 当构建完成后，单击在操作页面的右上角的'Artifacts`按钮下载二进制文件。

##使用方法
如果原来已经刷过openwrt系统，可将openwrt-*.img上传到tmp,然后使用命令： dd if=/tmp/openwrt-*.img of=/dev/sda写入。此命令将会清除原盘所有数据和分区，请注意备份。
默认WEB：192.168.1.1 用户名：root 密码：password

## 致谢

- [Microsoft](https://www.microsoft.com)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub](https://github.com)
- [GitHub Actions](https://github.com/features/actions)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cisco](https://www.cisco.com/)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)

## License

[失眠](https://github.com/1248429482/openwrt) © P3TERX
