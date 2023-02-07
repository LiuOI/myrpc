# 概述
- 使用protobuf进行数据的序列化和反序列化
- 使用muduo开源网络库进行网络通讯
- 使用zookeeper进行服务发现
# 预编译环境

1. protobuf
2. zookeeper
3. muduo
4. CMake
# 项目构建
```
./autobuild.sh
```
# 技术栈

- RPC远程调用原理及实现
- Protobuf数据序列化和反序列化协议
- ZooKeeper分布式一致性协调服务应用及编程
- muduo网络库编程
- 异步日志
- CMake构建项目集成编译环境
# 项目工程目录
bin：可执行文件<br />build：项目编译文件<br />lib：项目库文件<br />src：源文件<br />example：框架代码使用范例<br />CMakeLists.txt：顶层cmake文件<br />README.md：项目概述文件<br />autobuild.sh：一键编译脚本
