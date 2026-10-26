# asgard-cli releases

**English** | [繁體中文](#繁體中文)

Released builds of `asgard-cli`, the command line tool for Asgard FDE.

This repository holds releases and nothing else. The source is in a private
repository, and each release here is published from it by its release
workflow. Nothing here is edited by hand except this README.

## Install

On macOS or Linux:

```bash
curl -fsSL https://github.com/asgard-ai-platform/asgard-fde-cli-releases/releases/latest/download/install.sh | sh
```

On Windows, in PowerShell:

```powershell
irm https://github.com/asgard-ai-platform/asgard-fde-cli-releases/releases/latest/download/install.ps1 | iex
```

Both installers verify the download against the release's own checksums.
After that, `asgard-cli update` replaces the binary with the newest release,
and the tool tells you when there is one.

The other ways in - by hand, the `.pkg`, the `.deb`, `.rpm` and `.apk` - are in
the notes of the [latest release](https://github.com/asgard-ai-platform/asgard-fde-cli-releases/releases/latest).

To give the tool to somebody, send them the command rather than the file. On a
Mac, a file that arrives through a browser, a chat application, mail or AirDrop
carries the quarantine mark, and because the binaries are not notarized macOS
kills it on first run until the mark is cleared.

## 繁體中文

`asgard-cli`（Asgard FDE 的命令列工具）的發佈版本。

這個 repo 只放 release。原始碼在一個 private repo 裡，這裡的每個 release 都是由那個 repo 的發佈流程自動發上來的。除了這份 README，這裡沒有任何東西是手動編輯的。

macOS 或 Linux：

```bash
curl -fsSL https://github.com/asgard-ai-platform/asgard-fde-cli-releases/releases/latest/download/install.sh | sh
```

Windows，在 PowerShell 裡：

```powershell
irm https://github.com/asgard-ai-platform/asgard-fde-cli-releases/releases/latest/download/install.ps1 | iex
```

兩支安裝腳本都會對著 release 自己的 checksums 驗證下載的檔案。裝好之後，`asgard-cli update` 會換成最新的 release，有新版時工具也會提醒你。

其他安裝方式（手動、`.pkg`、`.deb`／`.rpm`／`.apk`）寫在[最新 release](https://github.com/asgard-ai-platform/asgard-fde-cli-releases/releases/latest) 的說明裡。

要交給別人安裝時，傳指令，不要傳檔案。在 Mac 上，透過瀏覽器、聊天軟體、郵件或 AirDrop 收到的檔案會帶 quarantine 標記，而這些 binary 沒有 notarize，所以 macOS 會在第一次執行時把它殺掉，直到標記被清掉為止。
