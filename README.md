<h3 >Hi 👋, I'm Riceball</h3>
<p>A self-taught frontend developer from Taiwan, Passionate about developing interesting web apps!</p>

- [📜 Resume](https://weweweb.pages.dev/en/resume/)
- [💼 Portfolio](https://weweweb.pages.dev/en/work/)
- [🏡 Personal Website](https://weweweb.pages.dev/en/)
- [📝 Blog](https://www.webdong.dev/en/)
---

<!--START_SECTION:feed-->
#### [JavaScript 陣列惰性求值透過 iterator helper](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;array-iterator-helper&#x2F;) 
先前提到 JavaScript 的 Iterator Protocol：什麼讓 JavaScript 資料結構能夠被迭代？ 了解 Iterator Protocol 與 Generator，而陣列正是基於 iterator 實做，自然受惠於近期推出的 iterator helper 來進行惰性求值。
#### [什麼讓 JavaScript 資料結構能夠被迭代？ 了解 Iterator Protocol 與 Generator](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;javascript-iterator&#x2F;) 
你有想過為什麼陣列可以被迭代處理（&#x60;for...of&#x60;）但物件不行嗎？Iterables 背後仰賴 Iterator Protocol 來實踐可被迭代的資料結構。基於 Iterator Protocol 的概念更是伸展到 Generator Function 相關的知識點，可以創造更多特殊的資料結構。
#### [實際簡白的 Monad 解釋](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;monad&#x2F;) 
Functor 的好處是：它讓我們能用同樣的方式操作不同的「容器型別」，想像成一個「裝值的盒子」，它允許我們對盒子裡的值進行運算，但同時又保留了盒子的結構。Functor 「提供了方式在容器裡操作值」，遵循同一性（Identity）與合成性（Composition）。
#### [實際簡白的 Applicative Functor 解釋](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-tw&#x2F;post&#x2F;applicative&#x2F;) 
從先前 Functor 的概念出發，Functor 的 &#x60;map&#x60; 只能作用在數值上，而不能是「存在於容器中的數值」上，所以才需要 Applicative Functor，一種比 Functor 更多功能的結構，除了滿足 Functor 的功能外還能「讓盒子裡的函數作用（apply）到另一盒子的值」。
#### [Function Composition and Pointfree Coding Style](https:&#x2F;&#x2F;www.webdong.dev&#x2F;en&#x2F;post&#x2F;pointfree&#x2F;) 
A coding style that emphasizes composing functions rather than handling specific data, defining functions without explicit parameters.
#### [Pointfree 代码风格通过函数组合提升代码质量](https:&#x2F;&#x2F;www.webdong.dev&#x2F;zh-cn&#x2F;post&#x2F;pointfree&#x2F;) 
一种代码风格，着重于函式的组合关系而非具体资料，定义函式时不显式提其参数（points），而是透过函式组合与高阶函式来表达资料流动。可以减少不必要的命名保持代码简洁与达成更好的通用组合性，但是额外的抽象须被理解与熟悉。透过两个实际案例熟悉 Pointfree 开发风格。
<!--END_SECTION:feed-->

