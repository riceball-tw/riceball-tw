<h3 >Hi 👋, I'm Riceball</h3>
<p>A self-taught frontend developer from Taiwan, Passionate about developing interesting web apps!</p>

- [📜 Resume](https://weweweb.pages.dev/en/resume/)
- [💼 Portfolio](https://weweweb.pages.dev/en/work/)
- [🏡 Personal Website](https://weweweb.pages.dev/en/)
- [📝 Blog](https://www.webdong.dev/en/)
---

<!--START_SECTION:feed-->
#### [Avoid path traversal by utilizing Go os.Root](https:&#x2F;&#x2F;www.webdong.dev&#x2F;en&#x2F;post&#x2F;go-avoid-path-traversal&#x2F;) 
Use Go 1.24&#39;s os.Root API to prevent path traversal when accessing local files; replace unsafe os.Open with os.Root or OpenInRoot.
#### [Go os.Root 预防路径遍历最佳实践](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-cn&#x2F;post&#x2F;go-avoid-path-traversal&#x2F;) 
最近在撰写的 Go 后端使用到大量的本地文件访问，其中最需要被防范的问题之一就是「路径遍历」。而在 Go 1.24 新增了 &#x60;os.Root&#x60; API 简洁优雅地避免安全问题。可以考虑所有 &#x60;os.Open&#x60; 的使用场景是否安全，并替换为 &#x60;os.Root&#x60; 确保「操作不应访问该目录之外的文件」。
#### [Go os.Root 預防路徑遍歷最佳實踐](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;go-avoid-path-traversal&#x2F;) 
最近在撰寫的 Go 後端使用到大量的本地檔案存取，其中最需要被防範的問題之一就是「路徑遍歷」。而在 Go 1.24 新增了 &#x60;os.Root&#x60; API 簡潔優雅的避免安全問題。可以考慮所有 &#x60;os.Open&#x60; 的使用情境是否安全，並替換上 &#x60;os.Root&#x60; 確保「操作不應存取該目錄之外的檔案」。
#### [代理伺服器與後端服務如何處理請求的 IP 來源？](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;gin-trusted-proxy&#x2F;) 
在服務面前擺一台 Nginx 進行反向代理是常見的操作，但當我們要做應用層的限流機制、紀錄 Log、一切與來源請求 IP 相關的功能時要如何拿到正確的資訊？記錄一下我根據 Go Gin 受信任代理設置官方文件的最佳範例。
#### [32-bit vs 64-bit systems](https:&#x2F;&#x2F;www.webdong.dev&#x2F;en&#x2F;post&#x2F;64bit-vs-32bit-system&#x2F;) 
I remember early PCs were 32-bit; around Windows 7 they moved to 64-bit. I wasn&#39;t sure what changed — some apps had two builds or needed compatibility mode.
#### [32-bits 与 64-bits 系统差异](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-cn&#x2F;post&#x2F;64bit-vs-32bit-system&#x2F;) 
还记得小时候的电脑都是 32-bits 的系统，大约在 win7 的时代已经逐步的替换成 64-bits 系统了，但我还是不了解具体来说有什么差异，只记得有段时间有两种软体规格可以选择，或是某些软体需要用「兼容模式」来执行。
<!--END_SECTION:feed-->

