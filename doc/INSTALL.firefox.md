
# Install for Firefox


## 此文撰寫環境

* Xubuntu 16.04 (64位元) 英文界面
* firefox 50.0


## 安裝操作步驟

啟動「[firefox](http://manpages.ubuntu.com/manpages/xenial/en/man1/firefox.1.html)」後，然後在網址列輸入「about:debugging」，按下「Enter」，

會出現一個畫面，有三個頁籤，分別是「Add-ons」，「Tabs」，「Workers」。

畫面預設開啟的頁籤是「Add-ons」，右上方有一個按鈕「Load Temporary Add-on」，按下該按鈕後，

找尋剛剛clone下來的專案，選擇「webextensions-search-ubuntu-tw/src/manifest.json」。

就會在下方多出一個項目「Search [www.ubuntu-tw.org](//www.ubuntu-tw.org)」。


## 移除操作步驟

在網址列輸入「about:addons」，按下「Enter」，

會出現一個畫面，有五個頁籤，分別是「Get Add-ons」，「Extensions」，「Appearance」，「Plugins」，「Searvices」。

點選「Extensions」這個頁籤，也會看到一個項目「Search [www.ubuntu-tw.org](//www.ubuntu-tw.org)」，該項目右方有兩個按鈕「Disable」和「Remove」。

按下「Remove」這個按鈕，就可以移除了。


## 額外參考

* MDN / [about:debugging](https://developer.mozilla.org/en-US/docs/Tools/about%3Adebugging#Enabling_add-on_debugging)
