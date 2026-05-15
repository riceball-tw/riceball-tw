<h3 >Hi 👋, I'm Riceball</h3>
<p>A self-taught frontend developer from Taiwan, Passionate about developing interesting web apps!</p>

- [📜 Resume](https://weweweb.pages.dev/en/resume/)
- [💼 Portfolio](https://weweweb.pages.dev/en/work/)
- [🏡 Personal Website](https://weweweb.pages.dev/en/)
- [📝 Blog](https://www.webdong.dev/en/)
---

<!--START_SECTION:feed-->
#### [Go struct 記憶體對齊如何提升記憶體運用效率](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;go-memory-aligment&#x2F;) 
在學習 Go 時會了解到 &#x60;struct&#x60; 其實就是一串自訂的資料結構，而其中欄位的「順序」將直接影響到在記憶體中所佔用的實際大小甚至程式的速度。了解記憶體對齊的概念除了「節省空間」外也能為打造「更佳的緩存局部性（Cache locality）」。
#### [Improving Go code quality through CI static validation](https:&#x2F;&#x2F;www.webdong.dev&#x2F;en&#x2F;post&#x2F;auto-format-go-in-ci&#x2F;) 
Noticed friction when committing Go code (tabs, alignment, minor formatting). Moving native Go static checks to CI enforces consistent formatting.
#### [在 CI 中通过自动化静态验证提升 Go 代码质量](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-cn&#x2F;post&#x2F;auto-format-go-in-ci&#x2F;) 
近期在开发 Go 专案时发现到提交代码流程总是有些摩擦，像是开发时习惯用 Tab 到 GitLab 上宽度就会变得很奇怪，或是一些简单的对齐问题都在无形消耗专注力。所以透过把一些原生的 Go 静态检查工具搬到 CI 上执行，确保统一的开发体验。
#### [於 CI 自動化靜態驗證 Go 提升代碼品質](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;auto-format-go-in-ci&#x2F;) 
近期在開發 Go 專案時發現到提交代碼流程總是有些摩擦，像是開發時習慣用 Tab 到 GitLab 上寬度就會變得很奇怪，或是一些簡單的對齊問題都在無形消耗專注力。所以透過把一些原生的 Go 靜態檢查工具搬到 CI 上執行，確保統一的開發體驗。
#### [透過 Go Slog 達成結構化寬事件 logging 最佳實踐](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;logging-in-go&#x2F;) 
最近有較多的時間思考開發上的最佳實踐，考慮到目前開發的一個後端項目基本就是拿 go 原生的 log 到處打印儲存片面狀態而已。在閱讀一些文件與最佳實踐後，我想著手改善現有的 logging 體驗透過導入 Go 1.21 引入的原生 slog 庫。
#### [平行程式開發：原子操作、鎖、信號量、具狀態 Goroutine](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;parallel-programming&#x2F;) 
大多程式都可以採取「並行 Concurrency」的方式來達成簡單安全且高效的運行，但隨著多核 CPU 出現以及特定場景對於效率的追求「平行 Parallelism」運行程式是另一個提高運行效率方向。本文練習透過 Go 複習平行程式開發下資料存取相關技巧：原子操作、鎖、信號量⋯⋯
<!--END_SECTION:feed-->

