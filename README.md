# How to play CTF

## 選擇領域
在玩CTF之前，可以先根據自己的背景知識來選擇要玩哪個領域，雖然並非絕對，  
但可幫助你在入門時更輕鬆，且更容易取得成就感(基本上就看粗體就行，其他只是稍微加分)。
### 無基礎
可以挑以下粗體項目有興趣的來學習，或直接參考以下學習資料。
### Web
(其實就是開發網站所常用的知識)
* 前端
	* HTML
	* CSS
	* **JavaScript**
* 後端
	* **PHP**
	* ASP
	* JSP
	* C#
* 資料庫
	* **SQL**
		* MySQL, Oracle, SQLite...
* 協定
	* **HTTP**
	* HTTPS
* 檔案格式
	* XML
	* JSON
* WWW伺服器
	* Apache, nginx...
* linux bash

### Pwn
* 語言
	* **C**
	* **ASM(x86)**
	* C++
	* 一個腳本語言
		* Python, PHP, Ruby...
* 底層知識
	* OS
* **Linux bash**
* 執行檔
	* ELF
	* PE

### Reversing
* 各架構的ASM
	* **x86**
	* ARM
	* MIPS

## 工具
俗話說工欲善其事，必先利其器，以下是我挑初經常會用到的工具，特別是剛開始非常需要/方便的。
### Web
* [BurpSuite](https://portswigger.net/burp)
* [Firefox HackBar](https://addons.mozilla.org/en-US/firefox/addon/hackbar/)
### Pwn & Reversing
* Debugger
	* linux
		* gdb
			* [gdb-peda](https://github.com/longld/peda)
	* windows
		* [x64dbg](https://x64dbg.com/#start)
* Python
	* [pwntools](https://github.com/Gallopsled/pwntools)
* IDA Pro

## 學習資源
挑幾個對我初學時非常有幫助的
* [LiveOverflow](http://liveoverflow.com/) - 應該是youtube上最棒的hacking教學了，從最簡單的到很深入的都有，並且有許多系列的課程，只可惜需要練英聽。
* [Bamboofox](https://bamboofox.cs.nctu.edu.tw/) - 臺灣良心，有講義有課程錄影，也有題目讓你練習(Pwn多一些)，還是中文資源。
* [HACKSPLAINING](https://www.hacksplaining.com/) - **Web**漏洞教學，非常簡單好懂，網站很精美！
* [RE for beginners](https://beginners.re/) - **Reversing**教學，網路有中文版，不過太大本很難啃，但對於沒什麼逆向基礎的來說可以很有系統化的學。
* [angelboy youtube](https://www.youtube.com/user/scwuaptx/videos) - 臺灣**Pwn**大神youtube頻道，影片看完後pwn基礎應該就都懂了。


## CTF網站
### 綜合
* [hackme](https://hackme.inndy.tw/) - 也是臺灣人架的，什麼類型題目都有。
* [pwnable.kr](http://pwnable.kr/) - 綜合**pwn**題目，應該是pwn領域最知名的網站。
* [CTFlearn](https://ctflearn.com/index.php) - 特色是題目有些是user自己出的。
* [RingZer0 CTF](https://ringzer0team.com/) - 題目的種類應該是最豐富的。

### 入門
* [picoCTF](https://picoctf.com/) - 設計給高中生玩的，超級精美，非常好入門。
* [overthewire](http://overthewire.org/wargames/) - 沒有linux基礎的非常適合玩這個，不但教資安也會教linux。

### 偏難
* [pwnable.tw](https://pwnable.tw/) - 高強度**pwn**題目，我玩了好一陣子。
* [reversing.kr](http://reversing.kr/) - 一系列**reversing**題目。
