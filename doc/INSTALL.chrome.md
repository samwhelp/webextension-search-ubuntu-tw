
# Install for Chrome or Chromium


## 此文撰寫環境

* Xubuntu 16.04 (64位元) 英文界面
* Chromium 53.0.2785.143


## 安裝操作步驟

啟動「[chromium-browser](http://manpages.ubuntu.com/manpages/xenial/en/man1/chromium-browser.1.html)」後，然後在網址列輸入「chrome://extensions/」，按下「Enter」，

會出現一個畫面，有四個頁籤，分別是「History」，「Extensions」，「Settings」，「About」。

畫面預設開啟的頁籤是「Extensions」，右上方有一個選項「Developer mode」，勾選改選項，

就會跑出三個按鈕，分別是「Load unpacked extension...」,「Packed extension...」,「Update extensions now」，

然後按下「Load unpacked extension...」

找尋剛剛clone下來的專案，選擇「webextensions-search-ubuntu-tw/src/」這個資料夾，按下「Open」按鈕。

就會在下方多出一個項目「Search [www.ubuntu-tw.org](//www.ubuntu-tw.org)」。


## 移除操作步驟

在剛剛的畫面，該項目右方有一個icon是垃圾桶的圖示，

按下後，會出現一個確認對話框，

按下「Remove」這個按鈕，就可以移除了。


## 額外參考

* developer.chrome / [Getting Started: Building a Chrome Extension](https://developer.chrome.com/extensions/getstarted)
