<p><img align="top" src="https://raw.githubusercontent.com/dex-ovo-studio/Mystery/main/assets/ui/guide.svg" alt="Mystery 使用指南 / User guide" width="100%"></p>

[← Mystery](https://github.com/dex-ovo-studio/Mystery) · [下载 / Download](https://github.com/dex-ovo-studio/Mystery/releases/tag/mystery-v2.1.0) · [版本状态 / Status](https://github.com/dex-ovo-studio/Mystery/blob/main/STATUS.md)

## 安装与启动 / Install & launch

1. 下载 [Windows x64 安装包](https://github.com/dex-ovo-studio/Mystery/releases/download/mystery-v2.1.0/DEX-Setup-2.1.0-x64.exe)。  
   Download the Windows x64 installer.
2. 升级前备份需要保留的本地资料，并退出正在运行的 Mystery。  
   Back up local data and quit the existing app before upgrading.
3. 运行安装包，按向导完成安装后启动软件。  
   Run the installer, follow setup, then launch the app.

安装包名称为 `DEX-Setup-2.1.0-x64.exe`；现有安装程序可能仍显示 D.E.X 品牌。  
The installer is named `DEX-Setup-2.1.0-x64.exe` and may display the earlier D.E.X branding.

## 文件校验 / File verification

需要核对下载文件时，可使用版本页的 [SHA256SUMS.txt](https://github.com/dex-ovo-studio/Mystery/releases/download/mystery-v2.1.0/SHA256SUMS.txt)。  
Use the release checksum list when you need to verify a downloaded file.

<details>
<summary>展开校验步骤 / Verification steps</summary>

```powershell
Get-FileHash -LiteralPath .\DEX-Setup-2.1.0-x64.exe -Algorithm SHA256
```

预期 SHA-256 / Expected SHA-256:

```text
ff206d3eece2740ea557cc46e8571341cd3acf4b74d073806eb99c5a0d126880
```

</details>

## 历史版本与反馈 / History & feedback

日常使用建议选择 2.1.0。旧版保留供回溯，不保证兼容当前账号服务。  
Use 2.1.0 for everyday use. Archived releases may not work with current account services.

[历史版本](https://github.com/dex-ovo-studio/Mystery/releases) · [状态页历史导航](https://github.com/dex-ovo-studio/DEX-Studio-Software-Status#mystery-history) · [官方网站与反馈 / Website & feedback](https://mystery.mydex.top)
