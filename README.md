<h3 >Hi 👋, I'm Riceball</h3>
<p>A self-taught frontend developer from Taiwan, Passionate about developing interesting web apps!</p>

- [📜 Resume](https://weweweb.pages.dev/en/resume/)
- [💼 Portfolio](https://weweweb.pages.dev/en/work/)
- [🏡 Personal Website](https://weweweb.pages.dev/en/)
- [📝 Blog](https://www.webdong.dev/en/)
---

<!--START_SECTION:feed-->
#### [道地 Go 語言 Enum 與 Union 實踐方式](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;go-enum-and-union&#x2F;) 
Go 既沒有 Enum（枚舉）也沒有 Union（聯合）的關鍵字，因此會使用現有的語言特性來達成相同的效果。藉由研究其他語言如 TypeScript 來了解如何重現相同的特性。Enum 組合 (const + iota)與Union 組合 (interface + struct)。
#### [道地 Go 錯誤處理模式： Must](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;go-must-pattern&#x2F;) 
最近用到 Go 官方 uuid 庫產生 UUID v7 時候留意到一種使用方式是：Must，他的描述也很簡單：Must returns uuid if err is nil and panics otherwise. 用途是「當錯誤不是一個可以恢復的選項時」，使用包裝好的 &#x60;Must&#x60; 直接 panic 錯誤。
#### [藉助 AI Loop 統一後端請求與回應格式](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;unify-request-and-response-utlizing-ai-with-goal&#x2F;) 
你有遇過格式不一的後端專案嗎？近期在翻新某個 Go 後端專案痛苦的因素就是請求與回應格式不一，這是一個很直白且簡單的問題，但實際會造成很大的困擾。藉由定義完整的 Agent Skills 文件與 goal 來自動達成目標。
#### [Avoid path traversal by utilizing Go os.Root](https:&#x2F;&#x2F;www.webdong.dev&#x2F;en&#x2F;post&#x2F;go-avoid-path-traversal&#x2F;) 
Use Go 1.24&#39;s os.Root API to prevent path traversal when accessing local files; replace unsafe os.Open with os.Root or OpenInRoot.
#### [Go os.Root 预防路径遍历最佳实践](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-cn&#x2F;post&#x2F;go-avoid-path-traversal&#x2F;) 
最近在撰写的 Go 后端使用到大量的本地文件访问，其中最需要被防范的问题之一就是「路径遍历」。而在 Go 1.24 新增了 &#x60;os.Root&#x60; API 简洁优雅地避免安全问题。可以考虑所有 &#x60;os.Open&#x60; 的使用场景是否安全，并替换为 &#x60;os.Root&#x60; 确保「操作不应访问该目录之外的文件」。
#### [Go os.Root 預防路徑遍歷最佳實踐](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;go-avoid-path-traversal&#x2F;) 
最近在撰寫的 Go 後端使用到大量的本地檔案存取，其中最需要被防範的問題之一就是「路徑遍歷」。而在 Go 1.24 新增了 &#x60;os.Root&#x60; API 簡潔優雅的避免安全問題。可以考慮所有 &#x60;os.Open&#x60; 的使用情境是否安全，並替換上 &#x60;os.Root&#x60; 確保「操作不應存取該目錄之外的檔案」。
<!--END_SECTION:feed-->

