<h3 >Hi 👋, I'm Riceball</h3>
<p>A self-taught frontend developer from Taiwan, Passionate about developing interesting web apps!</p>

- [📜 Resume](https://weweweb.pages.dev/en/resume/)
- [💼 Portfolio](https://weweweb.pages.dev/en/work/)
- [🏡 Personal Website](https://weweweb.pages.dev/en/)
- [📝 Blog](https://www.webdong.dev/en/)
---

<!--START_SECTION:feed-->
#### [Go 泛型使用筆記](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;go-generic&#x2F;) 
泛型解決的是「同一段邏輯要套在多種型別上」，不是「製造多餘的抽象」，明明邏輯一模一樣的函式，換個型別就得再複製貼上一份：SumInts、SumFloats、SumStrings。泛型從 Go 1.18 加進語言後這件事就有解了，且在 Go 1.27 還加入了泛型函式的功能。
#### [文字水印技術原理如何實現？](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;how-is-text-watermark-work&#x2F;) 
Anthropic 近期公告未來的模型都會替文字添加水印：How Claude&#39;s text watermark works，所以我想研究一下 LLM 文字水印是如何實現的且對使用者有什麼影響？主流的 SynthID-Text 運作方式與如何看待 AI 水印。
#### [Unifying Communication Between Services with gRPC](https:&#x2F;&#x2F;www.webdong.dev&#x2F;en&#x2F;post&#x2F;grpc&#x2F;) 
I spent a lot of time manually feeding the right context to the AI. gRPC uses protbuf as the single source of truth to solve the issue
#### [通过 gRPC 统一服务之间的通信](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-cn&#x2F;post&#x2F;grpc&#x2F;) 
服务之间对同一笔数据有不同的命名与定义，是多存储库架构最常见的痛点，也让 AI 难以获得一致的上下文。gRPC 以 Protocol Buffers 作为唯一真实来源，用一份 .proto 生成各语言的类型与客户端，让字段命名与缺漏问题在编译期就被挡下来。
#### [透過 gRPC 統一服務之間溝通](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;grpc&#x2F;) 
服務之間對同一筆資料有不同的命名與定義，是多儲存庫架構最常見的痛點，也讓 AI 難以取得一致的上下文。gRPC 以 Protocol Buffers 作為唯一真實來源，用一份 .proto 產生各語言的型別與客戶端，讓欄位命名與缺漏問題在編譯期就被擋下來。
#### [Building Relational Queries in Go MongoDB](https:&#x2F;&#x2F;www.webdong.dev&#x2F;en&#x2F;post&#x2F;go-mongodb-relation-join&#x2F;) 
Recently at work I’ve been running into the problem of doing relational queries in Mongo. If not handled properly, it can easily turn into an N+1 problem.
<!--END_SECTION:feed-->

