<h3 >Hi 👋, I'm Riceball</h3>
<p>A self-taught frontend developer from Taiwan, Passionate about developing interesting web apps!</p>

- [📜 Resume](https://weweweb.pages.dev/en/resume/)
- [💼 Portfolio](https://weweweb.pages.dev/en/work/)
- [🏡 Personal Website](https://weweweb.pages.dev/en/)
- [📝 Blog](https://www.webdong.dev/en/)
---

<!--START_SECTION:feed-->
#### [研究透過 LangChain 替產品導入本地模型與配套 Harness](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;build-a-local-llm-agent-inside-product&#x2F;) 
這個時代開發產品絕對會被反覆要求「我們的產品能不能整合 AI？」、「AI 能帶來什麼新的商機？」，很多團隊包括我也是第一次遇到需要整合 AI 到實際產品的情況。而我在開發的產品性質又是需要斷網的嚴苛環境，因此這篇文章主要研究盡可能基於瀏覽器或本地 LLM 的 MVP，著重探討技術上的可能性。
#### [Handling Parallel Image Generation in Go](https:&#x2F;&#x2F;www.webdong.dev&#x2F;en&#x2F;post&#x2F;go-handling-parallel-image-generation&#x2F;) 
Worker Pool patterns is a great entry point: “keep a fixed number of workers, waiting for work to be assigned to them.”
#### [Go 缓冲通道实践工作池处理并发图片生成](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-cn&#x2F;post&#x2F;go-handling-parallel-image-generation&#x2F;) 
学习 Go 时我一直想找个机会尝试并发场景，而一个最基础的 Worker Pool（Thread Pool）就是很好的入门模式：「让固定数量的 worker 在后台运行，等待分配给它们工作」。这个场景很适合练习并发，因为每张图片彼此独立，不需要等前一张完成才能生成下一张，但也不能无限制地全部同时运行。
#### [Go 緩衝通道實踐工作池處理併發圖片生產](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;go-handling-parallel-image-generation&#x2F;) 
學習 Go 我一直想找個機會嘗試併發情境，而一個最基礎的 Worker Pool（Thread Pool）就是很好入門的模式：「讓固定數量的 worker 在背後運行，等待分配給它們工作」。這個情境很適合練習併發，因為每張圖片彼此獨立，不需要等前一張完成才能生成下一張，但也不能無限制地全部同時跑。
#### [What is nonce?](https:&#x2F;&#x2F;www.webdong.dev&#x2F;en&#x2F;post&#x2F;what-is-nonce&#x2F;) 
A nonce is a value used only once and can take any form, The key is to verify &quot;each operation must be unique&quot;
#### [仅使用一次的随机数，nonce 是什么？](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-cn&#x2F;post&#x2F;what-is-nonce&#x2F;) 
在先前写给网页开发者的 CSRF 理解与防范提到其中一种防范方式是透过生成 CSRF Token，而这其实算是一种 Nonce。 Nonce 等于只用一次的数值，可以是任何形式的资料：数字、字串、递增计数器、时间戳……重点在验证「每一次操作都必须唯一」，攸关重要行动的地方都会用到 nonce。
<!--END_SECTION:feed-->

