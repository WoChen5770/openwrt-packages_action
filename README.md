openwrt-packages
国内常用OpenWrt软件包源码合集，每天自动更新

18.06版luci请使用packages分支

19.07版luci请使用packages-19.07分支

lean源码用主分支，op官方源码用packages-19.07

食用方式（三选一，这里以18.06为例）：
还是建议按需取用，不然碰到依赖问题不太好解决

先cd进package目录，然后执行
 git clone https://github.com/WoChen5770/openwrt-packages
或者添加下面代码到feeds.conf.default文件
 src-git WoChen5770_packages https://github.com/WoChen5770/openwrt-packages
先cd进package目录，然后执行
 svn co https://github.com/WoChen5770/openwrt-packages/branches/packages-18.06
