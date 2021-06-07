# 嵌入式GCC开发工具列表

1. 编译器：gcc-arm-none-eabi 

2. 构建和管理工程：make （makefile）

3. 烧录调试工具：openocd


# 嵌入式GCC环境搭建

## mac


1. Xcode command line tools 安装，该工具有许多工具集包括make、gcc等等；也可以直接安装Xcode
	```
	xcode-select --install
	````

2. 安装brew软件包管理工具(用于安装其他软件，方便)
	官网安装命令：
	```
	/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
	```
	国内安装命令： 
	```
	/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
	```

3. 安装gcc-arm-none-eabi；在brew中名称为gcc-arm-embedded
	```
	brew install gcc-arm-embedded
	```




## linux(ubuntu)





## windows

