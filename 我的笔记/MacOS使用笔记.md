MacOS使用笔记

MacOS使用笔记

系统工具类

1. 安装命令行工具（内部包含git，svn等） 终端输入：xcode-select --install
2. 安装home brew 官网链接：https://brew.sh/index_zh-cn 功能扩展：https://github.com/buo/homebrew-cask-upgrade，扩展brew cu
3. 安装oh-my-zsh 官网链接：https://github.com/ohmyzsh/ohmyzsh 说明：安装前请确保系统默认shell为zsh，macOS系统10.14.x版本默认为bash，10.15.x版本默认为zsh 功能扩展：通过brew下载zsh-syntax-highlighting，打开～/.zshrc配置文件，追加配置 source /usr/local/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh，提供语法高亮功能

开发环境

Java

1. JDK安装，oracle-jdk，版本1.8，注意：关闭java更新
2. 集成开发环境  a. maven 官网链接：http://maven.apache.org，下载免安装版本 修改配置文件，指定本地仓库位置，更换阿里镜像，链接：https://help.aliyun.com/document_detail/102512.html#h2-u914Du7F6Eu6307u53572 修改intellij-idea中maven相关配置 b. git/svn 确认intellij-idea中相关配置 c. intellij-idea lombok插件 以.开头文件过滤，编译后文件过滤

Docker

1. 通过brew下载安装docker
2. Preferences-General关闭跟随系统启动，关闭自动检查更新，关闭反馈
3. Preferences-Daemon 添加docker中国加速镜像https://registry.docker-cn.com
4. 浏览https://hub.docker.com，查找相关镜像（版本信息等）
