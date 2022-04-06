# 秋水Beanfun登录工具

![logo](./logo.png)

本工具不是遊戲橘子數位科技開發的官方工具

使用易語言進行開發。

**注意：1.x系列不再维护**

**建议使用Java编写版本[QsBeanfun](https://github.com/starmcc/qs-beanfun)**

引用LR區域模擬元件，支持32bit和64Bit台服新楓之谷遊戲。

參考了[pungin](https://github.com/pungin)的實現思路。

本工具僅支持臺服新楓之谷使用，如果有其他遊戲需要，建議使用[pungin/Beanfun: 繽放](https://github.com/pungin/Beanfun)

開源遵循MIT協議，如遇到問題或Bug 歡迎提交 Issues。

[具體實現方案，各種語言領域的大佬歡迎查閱](https://github.com/starmcc/QsBeanfunLogin/tree/master/docs)

## Download

[Releases](https://github.com/starmcc/QsBeanfunLogin/releases)選擇最新版本`QsBeanfunLogin.exe`程式下載

## Implementation

1. 免IE方式登入Beanfun香港橘子賬號
2. 簡體環境運行臺服新楓之谷（LR作者支持）
3. 裝備卷軸計算器（收集了各種資料做出來的壹個計算器）
4. 免輸入賬密直接進入遊戲（與網頁登錄實現方式相同）
5. 實時中臺匯率計算
6. 集成各種優化小功能，快捷操作等


## Environment

- [Microsoft Visual C++ Redistributable](https://docs.microsoft.com/zh-CN/cpp/windows/latest-supported-vc-redist?view=msvc-170)
- Windows7 以上
- .net Framework 4.8 以上


## Usage

下載`QsBeanfunLogin.exe`後，直接運行。

第一次運行如未安裝橘子官方`Beanfun`插件則會提示前往下載。

遊戲會在系統臨時目錄釋放所需依賴文件。

系統臨時目錄一般是

`C:\Users\系統用戶名\AppData\Local\Temp\QsBeanfunLogin`

- `act.edb` 賬密保存庫，用於記住密碼。
- `config.ini` 用於記錄工具配置信息。
- `LR*` 帶LR開頭文件是LR的區域模擬元件。

## Built With

- [精易模塊 10.0.5](https://bbs.125.la) - 易語言模塊
- [精易皮膚模塊 5.0](https://bbs.125.la/thread-14660006-1-1.html)  - 易語言模塊
- [Locale_Remulator](https://github.com/InWILL/Locale_Remulator) 區域模擬元 1.4.3


## Developer

> 左鍵點擊 LOGO 15次以上

- 會進入開發者模式
- 會在系統桌面生成請求日誌文件，請求會有打印。

> 右鍵點擊 LOGO 15次以上

- 可設置請求代理，可供抓包學習。