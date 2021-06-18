# openwrt-packages
为了方便编译，收集常用的OpenWrt软件包源码。
每天定时自动更新

18.06版luci请使用master分支

19.07版luci请使用19.07分支


## 食用方式（方法3为18.06例子）：
`还是建议按需取用，不然碰到依赖问题不太好解决`
1. 先cd进package目录，然后执行
```bash
 git clone https://github.com/WoChen5770/openwrt-packages
```
2. 或者添加下面代码到feeds.conf.default文件
```bash
 src-git WoChen5770_packages https://github.com/WoChen5770/openwrt-packages
```
3. 先cd进package目录，然后执行
```bash
 svn co https://github.com/WoChen5770/openwrt-packages/branches/master
```
