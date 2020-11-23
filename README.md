# AutoBuild-OpenWrt

感谢P3TERX、esir的付出

自动云编译openwrt固件
适配：x64、R619AC
固件来源：lean'openwrt git仓库

添加、passwall、adguard、openclash等插件

使用方法：更新对应*.config配置文件，x86-x64v1版为内核配置版本，x86-x64kernel.config为内核配置文件，x86-x64v2为默认内核配置文件，R619AC.config就是字面意思。

Build OpenWrt firware [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) using GitHub Actions  
Hereby thank P3TERX for his amazing job: https://github.com/P3TERX/Actions-OpenWrt/


## Usage

- Sign up for [GitHub Actions](https://github.com/features/actions/signup)
- Fork [this GitHub repository](https://github.com/esirplayground/AutoBuild-OpenWrt)
- Click [.github/workflows] folder on the top of repo and you could see few workflow files, Each for one particular architecture(device).
- Edit the workflow file you desire，uncomment push section 3 lines together and submit the commit.(Other 2 methods wait you to discover)
- The build starts automatically. Progress can be viewed on the Actions page.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.
- Default Web Admin IP: `192.168.1.1`, username `root`，password `password`


