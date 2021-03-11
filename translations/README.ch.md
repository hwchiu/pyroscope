<p align="center"><img alt="Pyroscope" src="https://user-images.githubusercontent.com/662636/105129037-11334180-5a99-11eb-8951-1d4aaaed50de.png" width="500px"/></p>


[![Tests Status](https://github.com/pyroscope-io/pyroscope/workflows/Tests/badge.svg)](https://github.com/pyroscope-io/pyroscope/actions?query=workflow%3ATests)
[![Apache 2 License](https://img.shields.io/badge/license-Apache%202-blue.svg)](LICENSE)
[![Latest release](https://img.shields.io/github/release/pyroscope-io/pyroscope.svg)](https://github.com/pyroscope-io/pyroscope/releases)
[![GoDoc](https://godoc.org/github.com/pyroscope-io/pyroscope?status.svg)](https://godoc.org/github.com/pyroscope-io/pyroscope)

<h2>
  <a href="https://pyroscope.io/">官網</a>
  <span> • </span>
  <a href="https://pyroscope.io/docs">文件</a>
  <span> • </span>
  <a href="https://demo.pyroscope.io/">示範網站</a>
  <span> • </span>
  <a href="/examples">範例</a>
  <span> • </span>
  <a href="https://pyroscope.io/slack">SLACK 頻道</a>
</h2>

Pyroscope 是個基於開放原始碼的效能分析平台，其能夠幫助你:
* 找出程式碼中效能問題
* 解決 CPU 高使用率的問題
* 幫助瞭解應用程式的運作細節，譬如 Call Trace
* 隨時間去追蹤任何系統變化

## Live Demo

[🔥 Pyroscope的Live Demo🔥](https://demo.pyroscope.io/)

[![Pyroscope GIF Demo](https://user-images.githubusercontent.com/662636/105124618-55b9df80-5a8f-11eb-8ad5-0e18c17c827d.gif)](https://demo.pyroscope.io/)


## 特色

* 能夠幫助多個應用程式儲存多年的系統分析資料
* 透過時間區間或特定事件來檢視多年儲存資料
* 低CPU 開銷
* 資料壓縮效率高，硬碟空間需求低
* 簡潔易用的UI
* 支持 Go、Ruby、Python 等程式語言

## 三步驟架設 Pyroscope 於本地環境:

```shell
# install pyroscope
brew install pyroscope-io/brew/pyroscope

# start pyroscope server:
pyroscope server

# in a separate tab, start profiling your app:
pyroscope exec python manage.py runserver
```

## 說明文件

請查看下列文件來學習如何使用 Pyroscope 於其他程式語言上、安裝於 Linux 環境或是部署於生產環境中:
* [文件說明](https://pyroscope.io/docs/)
* [部署說明書](https://pyroscope.io/docs/deployment)
* [開發人員說明書](https://pyroscope.io/docs/developer-guide)


## 部署圖樣

![Deployment Diagram](../.github/markdown-images/deployment.svg)

## 下載方式

你可以從[Downloads page](https://pyroscope.io/downloads/) 中下載最新版本的 pyroscope, 目前支援 macOS, Linux 及 Docker 等多種平台

## 支持的程式語言

* [x] Ruby
* [x] Python
* [x] Go
* [x] Node
* [ ] Linux eBPF (即將到來)

有任何想要支持的語言請歡迎到 Slack 上告訴開發團隊 [our slack](https://pyroscope.io/slack).

## 如何貢獻 

請查看我們的貢獻守則來瞭解如何加入成為貢獻者。 [Contributing Guide](/CONTRIBUTING.md)

### 感謝全部幫助發展Pyroscope的貢獻者！

[//]: contributor-faces
<a href="https://github.com/petethepig"><img src="https://avatars.githubusercontent.com/u/662636?v=4" title="petethepig" width="80" height="80"></a>
<a href="https://github.com/Rperry2174"><img src="https://avatars.githubusercontent.com/u/23323466?v=4" title="Rperry2174" width="80" height="80"></a>
<a href="https://github.com/LouisInFlow"><img src="https://avatars.githubusercontent.com/u/73438887?v=4" title="LouisInFlow" width="80" height="80"></a>
<a href="https://github.com/abaali"><img src="https://avatars.githubusercontent.com/u/37961057?v=4" title="abaali" width="80" height="80"></a>
<a href="https://github.com/ekpatrice"><img src="https://avatars.githubusercontent.com/u/77462462?v=4" title="ekpatrice" width="80" height="80"></a>
<a href="https://github.com/cmonez"><img src="https://avatars.githubusercontent.com/u/39146411?v=4" title="cmonez" width="80" height="80"></a>
<a href="https://github.com/Pranay0302"><img src="https://avatars.githubusercontent.com/u/55592629?v=4" title="Pranay0302" width="80" height="80"></a>
<a href="https://github.com/geoah"><img src="https://avatars.githubusercontent.com/u/88447?v=4" title="geoah" width="80" height="80"></a>
<a href="https://github.com/yveshield"><img src="https://avatars.githubusercontent.com/u/8733258?v=4" title="yveshield" width="80" height="80"></a>

[//]: contributor-faces
