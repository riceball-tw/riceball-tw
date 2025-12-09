<h3 >Hi 👋, I'm Riceball</h3>
<p>A self-taught frontend developer from Taiwan, Passionate about developing interesting web apps!</p>

- [📜 Resume](https://weweweb.pages.dev/en/resume/)
- [💼 Portfolio](https://weweweb.pages.dev/en/work/)
- [🏡 Personal Website](https://weweweb.pages.dev/en/)
- [📝 Blog](https://www.webdong.dev/en/)
---

<!--START_SECTION:feed-->
#### [ASCII、Unicode、UTF-8、UTF-16？電腦是如何處理文字的？](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;how-do-computers-process-text&#x2F;) 
近期在 Go 處理字串時發現對於電腦處理文字的原理不是很透徹，所以翻了更多教學文件了解電腦是如何處理文字的。歷史上電腦如何處理文字？以及後續 ASCII、Unicode、UTF-8、UTF-16 相關演進特點與背後取捨，了解為什麼現代文字編碼都使用 UTF-8。
#### [Go 字串處理使用 Rune](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;go-rune-and-characters&#x2F;) 
當在 Go 字串中索引位置 &#x60;n&#x60; 時，為什麼沒有得到第 &#x60;n&#x60; 個字元？相較於其他程式語言一串文字在遍歷時會預期拿到單一個字符，在 Go 會拿到「Rune」；如果直接透過索引取得 string 內容會拿到 byte。透過實際解 Codewars 題目了解處理字串要留意的東西
#### [Go Struct Tag and reflect](https:&#x2F;&#x2F;www.webdong.dev&#x2F;en&#x2F;post&#x2F;go-struct-tag&#x2F;) 
When interacting with MongoDB, I encountered unfamiliar syntax in Struct fields. This article explores why Go Struct Tags exist and the problems they solve.
#### [Go Struct Tag 是什麼？如何透過 reflect 動態處理欄位？](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;go-struct-tag&#x2F;) 
最近在與 MongoDB 互動時發現 Struct 欄位結尾有一段語法不是很熟悉，這篇文章探討 Struct Tag 存在的原因以及解決什麼問題。與其命令式的操縱資料，透過宣告式的方式來描述資料格式是 Struct Tag 的主要用途。
#### [Go Struct Tag 是什么？如何透过 reflect 动态处理栏位？](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-cn&#x2F;post&#x2F;go-struct-tag&#x2F;) 
最近在与 MongoDB 互动时发现 Struct 栏位结尾有一段语法不是很熟悉，这篇文章探讨 Struct Tag 存在的原因以及解决什么问题。与其命令式的操纵资料，透过宣告式的方式来描述资料格式是 Struct Tag 的主要用途。
#### [Go 非同步運算 (Goroutine)](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;go-multi-tasks&#x2F;) 
Goroutine 是由 Go 語言本身管理的輕量級執行緒（User-space Thread），而不是由作業系統管理的執行緒（OS Thread）。背後使用 M:N 排程模型。這意味著，M 個 Goroutine 會被分配到 N 個作業系統執行緒（OS Threads）上執行。
<!--END_SECTION:feed-->

