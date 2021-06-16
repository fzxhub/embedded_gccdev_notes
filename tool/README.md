# 嵌入式GCC开发工具安装
1. 编译器：gcc-arm-none-eabi 
2. 构建和管理工程：make （makefile）
3. 烧录调试工具：openocd
4. 编辑软件：VScode、vim 等任选一种
## mac嵌入式GCC环境
### mac工具列表
- Xcode command line tools或者Xcode（包含make等相关工具）
- brewhome（软件管理工具，这里主要用于安装gcc-arm-embedded、openocd）
- gcc-arm-embedded（嵌入式交叉编译工具）
- openocd（烧录调试工具）
### mac工具命令行安装步骤
1. Xcode command line tools 安装；或者直接安装Xcode也可。
```
xcode-select --install
````
2. 安装brew软件包管理工具(用于安装其他软件，方便)
	- 官网安装命令：
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
- 国内安装命令： 
```
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
```
3. 安装gcc-arm-none-eabi；在brew中名称为gcc-arm-embedded
```
brew install gcc-arm-embedded
```
### mac下载工具包方式手动安装
待更新
## linux(ubuntu)
### linux工具列表
1. gcc（一般都自带，如没有使用apt安装，主要使用make等工具）
2. gcc-arm-none-eabi（编译工具）
3. openocd（烧录调试工具）
### linux工具命令行安装步骤
1. 安装gcc
```
sudo apt install gcc
```
2. 安装gcc-arm-none-eabi
```
sudo apt install gcc-arm-none-eabi
```
3. 安装openocd
```
sudo apt install openocd
```
### linux下载工具包方式手动安装
待更新
## windows
### windows工具列表
1. mingw64（主要使用make等工具）
2. gcc-arm-none-eabi（编译工具）
3. openocd（烧录调试工具）
### windows工具命令行安装步骤
待更新；windows有软件管理工具winget，但是软件还比较少，暂不推荐
### 下载工具包方式手动安装
1. 下载mingw64；可使用安装包或者绿色包
2. 下载gcc-arm-none-eabi；可使用安装包或者绿色包
```
https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads
```
3. 下载openocd；可使用安装包或者绿色包
4. 确保mingw64、gcc-arm-none-eabi、openocd的bin目录在环境变量中


# 嵌入式GCC开发步骤



作者：fzxhub
联系：fzxhub@gmail.com