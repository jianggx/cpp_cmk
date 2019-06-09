## 本项目为测试 Cpp+Vscode+Mac 环境下的cpp开发

参考 https://vector-of-bool.github.io/docs/vscode-cmake-tools/index.html 

环境安装：

- 安装 vscode
- 安装 C/C++ tools 扩展： ms-vscode.cpptools
- 安装 CMake Tools 扩展

初始化项目：

    vsc command pallete: CMake: Quick Start
    填写 project name
    选择 kit： clang
    选择 project type： excutable

配置 - CMake Configuring;

    从vsc 的状态栏中启动配置，或者
    vsc command pallete: CMake: Configure
    生成build 目录，默认generator为Ninja

生成 - CMake Build

    从vsc 的状态栏中启动构建，或者
    vsc command pallete: CMake: Build
    生成的可执行程序在build 目录下

调试 - Debug

    通过launch.json

运行（非调试）

    vsc command pallete: CMake: Execute