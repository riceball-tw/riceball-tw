<h3 >Hi 👋, I'm Riceball</h3>
<p>A self-taught frontend developer from Taiwan, Passionate about developing interesting web apps!</p>

- [📜 Resume](https://weweweb.pages.dev/en/resume/)
- [💼 Portfolio](https://weweweb.pages.dev/en/work/)
- [🏡 Personal Website](https://weweweb.pages.dev/en/)
- [📝 Blog](https://www.webdong.dev/en/)
---

<!--START_SECTION:feed-->
#### [僅使用一次的隨機數，nonce 是什麼？](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;what-is-nonce&#x2F;) 
在先前寫給網頁開發者的 CSRF 理解與防範提到其中一種防範方式是透過生成 CSRF Token，而這其實算是一種 Nonce。Nonce 等於只用一次的數值，可以是任何形式的資料：數字、字串、遞增計數器、時間戳……重點在驗證「每一次操作都必須唯一」，攸關重要行動的地方都會用到 nonce。
#### [Idiomatic Go: Enum and Union](https:&#x2F;&#x2F;www.webdong.dev&#x2F;en&#x2F;post&#x2F;go-enum-and-union&#x2F;) 
Go lacks enum and union keywords; utlizing existing features to achieve the same patterns. study TypeScript as example
#### [地道 Go 语言 Enum 与 Union 实践方式](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-cn&#x2F;post&#x2F;go-enum-and-union&#x2F;) 
Go 既没有 Enum（枚举）也没有 Union（联合）的关键字，因此会使用现有的语言特性来达到相同效果。参考 TypeScript，使用 Enum 组合 (const + iota) 与 Union 组合 (interface + struct)。
#### [道地 Go 語言 Enum 與 Union 實踐方式](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;go-enum-and-union&#x2F;) 
Go 既沒有 Enum（枚舉）也沒有 Union（聯合）的關鍵字，因此會使用現有的語言特性來達成相同的效果。藉由研究其他語言如 TypeScript 來了解如何重現相同的特性。Enum 組合 (const + iota)與Union 組合 (interface + struct)。
#### [Idiomatic Go error-handling pattern: Must](https:&#x2F;&#x2F;www.webdong.dev&#x2F;en&#x2F;post&#x2F;go-must-pattern&#x2F;) 
Go&#39;s uuid v7 uses Must: returns uuid if err is nil and panics otherwise — use when the error isn&#39;t recoverable.
#### [地道 Go 错误处理模式：Must](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-cn&#x2F;post&#x2F;go-must-pattern&#x2F;) 
最近用到 Go 官方 uuid 库产生 UUID v7 时候留意到一种使用方式是：Must，他的描述也很简单：Must returns uuid if err is nil and panics otherwise. 用途是「当错误不是一个可以恢复的选项时」，使用包装好的 &#x60;Must&#x60; 直接 panic 错误。
<!--END_SECTION:feed-->

