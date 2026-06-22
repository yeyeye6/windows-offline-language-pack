# Windows Server 2022 简体中文离线安装

## 适用系统

- Windows Server 2022
- x64 / amd64
- 主构建号：20348

## 文件下载

语言 CAB 文件请前往 Releases 页面下载：

[下载 Windows Server 2022 中文语言包](https://github.com/yeyeye6/windows-offline-language-pack/releases/tag/server-2022-v1.0.0)

## 基础安装

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
.\install_zhcn.ps1
```

## 完整安装

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
.\install_zhcn.ps1 -InstallOptionalFeatures
```

## 安装后检查

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
.\install_zhcn.ps1 -CheckOnly
```
