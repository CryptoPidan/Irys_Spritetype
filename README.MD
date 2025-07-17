# Irys_Spritetype 打字小游戏脚本

## 🚀简介  
#### 这是一个 **护肝型脚本**，用于自动完成 Irys 平台上的打字小游戏任务。

## 📝功能说明  
- 启动时可自定义每组账号执行**N次**打字小游戏  
- 支持两种运行模式：  
  - **安全模式**：每次打字之间间隔 **35 秒**（基于游戏风控频率）  
  - **极速模式**：每次打字之间间隔 **1 秒**（高风险，适合测试）
- 自动识别并修正 EVM 地址为标准 EIP-55 校验和格式  
- 每天循环运行
- 任务完成后可在银河打卡  
- 自动计算 **准确率、WPM、字符数** 等信息  
- **无需私钥**

## 🖥️ 系统支持
* Windows、Linux、macOS

## 📋 使用说明
1. 安装 [.NET 9 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)
```
   >  Windows 用户：请选择 `SDK -> Windows -> x64 / x86`  
   >  macOS 用户：请选择 `SDK -> macOS -> Arm64 / x64`  
   >  如果你不打算修改代码或编译源码，可以直接下载并运行已编译好的 [Release]
```
2. 打开终端（CMD / PowerShell / Terminal），进入项目目录：
```
   cd path/to/your/project
```
3. 运行脚本：
```
   dotnet run
```


## 📦 文件结构

* `Address.txt`：每行一个以太坊地址
* `Proxy.txt`：每行一个代理，支持以下格式（不支持SOCKS)：

```txt
ip:port
http://ip:port
https://ip:port
http://username:password@ip:port
https://username:password@ip:port
```

* `Log.txt`：运行日志自动写入本文件




## 🌌 运行截图  
下图为脚本运行时的终端界面示意：

![运行截图](screenshot.png)



## 🤝 贡献指南

欢迎提交 Issues 或 Pull Requests

---



