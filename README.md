# The-Duolingo-Handbook-zh-TW
The Duolingo Handbook 正體中文翻譯

這是個人興趣所做的翻譯，版權為 Duolingo 所有。

## The Duolingo Handbook

<img src="https://github.com/goescat/The-Duolingo-Handbook-zh-TW/blob/main/image/The_Duolingo_Handbook-01.png" width="400">

官方連結：
https://blog.duolingo.com/handbook/

How Duolingo works: 14 years of big learnings in one little handbook.

## 內容

### Letter from Luis | 來自 Luis 的信
Duolingo is a quirky place.

Our culture wasn’t copied from a tech startup playbook. It was built from scratch by a few dozen nerds in an office above a sports bar in Pittsburgh, Pennsylvania.

For most of our early employees, Duolingo was their first real job. Without much experience, we had to experiment our way through the basic questions: Who should we hire? What’s the best way to build an app? How should we organize ourselves to build it? Doing it this way took time. But in the end, nothing could have been better for our culture and success.

Over time, we’ve sharpened our answers to these questions and many more. Now, fourteen years in, we’ve decided to put these answers into writing, and articulate how we do things.

At the center of this book are five principles. These aren’t aspirational—they’re lessons we've learned through experience. But they’re also living ideas: they have tensions within them, and there are places where they don’t always fit. We hope you study them, challenge them, and help us make the next version of this book even better.

Thanks for reading.

And welcome to Duolingo.

— Luis

> Duolingo 是個奇特的地方。
>
> 我們的文化不是照搬某家科技新創公司的成功範本，而是由一群宅宅，在美國賓州匹茲堡一家運動酒吧樓上的辦公室裡，從零開始打造出來的。
>
> 對我們早期的大多數員工來說，Duolingo 是他們第一份正式的工作。我們沒有太多的經驗，得靠不斷嘗試來解決最基本的問題：我們應該聘請什麼樣的人？怎麼打造一款優秀的 app？我們應該如何組織團隊來打造它？這樣的摸索花了不少時間，但到頭來，這正是塑造我們文化和成功的關鍵。
>
> 隨著時間推進，我們對這些問題的答案越來越清晰，還學到了更多新的經驗。如今，十四年過去了，我們決定把這些經驗整理成冊，清楚表達我們是如何做事的。
>
> 這本書的核心，是五大原則。它們並不是遙不可及的理想——而是我們親身經歷學到的寶貴經驗。但這些原則也不是絕對的，其中有矛盾、有取捨，甚至有時未必適用於所有情境。我們希望你能細讀它們、挑戰它們，然後幫助我們讓這本書的下個版本變得更好。
>
> 感謝你的閱讀。
> 歡迎來到 Duolingo。
>
> — Luis

### TL;DR | 太長了，重點摘要

Take the Long View
* We’re building a forever product that puts long-term user retention first.
* We hire exceptional people who will grow with Duolingo and shape its future for years to come.
* We’re creating a 100-year brand with delightful, quirky characters that become a part of learners’ lives.
> 長遠考量
> * 我們正在打造一個永續的產品，以長期使用者留存為首要目標。
> * 我們聘請優秀的人才，能與 Duolingo 一同成長，並在未來數年塑造它的發展。
> * 我們正在建立一個百年品牌，以充滿趣味且獨特的角色，成為學習者生活的一部分。

Raise the Bar
* Every feature we ship must be intuitive, delightful, useful, and polished.
* We make sure critical tasks have a clear owner.
* We constantly dogfood our products to identify bugs and propose improvements.
* We give candid feedback that focuses on the “what” and not the “who.”

> 樹立標竿
> * 我們推出的每個功能都必須直覺好用、令人愉悅、實用，且精心打磨。
> * 我們確保每項關鍵任務都有明確的負責人。
> * 我們親自使用自家產品，發現錯誤並提出改善方案。
> * 我們給予坦誠的回饋，對事而不對人。

Ship It
* We optimize “clock speed,” minimizing gaps between steps to maintain momentum.
* We run hundreds of experiments each week in order to constantly improve our products and our organization.
* We ruthlessly prioritize projects with the highest impact and quickly cut what isn’t working.
* We’ll only introduce a new process if it helps us make faster, better decisions.

快速執行
* 我們最佳化「時脈」，縮短每個階段間的間隔，以保持動力。
* 我們每週進行數百個實驗，不斷改進我們的產品與組織。
* 我們冷酷的以最具影響力的專案為優先，並迅速淘汰無效專案。
* 我們只會引入能幫助我們更快、更好做出決定的新流程。

Show Don’t Tell
* We lead with the results of our work, not the story of its effort.
* Our products don’t have to explain themselves—they should
be intuitive to everyone.
* When we disagree, we test ideas and let the metrics decide.

> 多說無益
> * 我們注重的工作的成果，而非過程有多艱辛。
> * 我們的產品應該對於任何人都直覺易懂，不需要額外說明。
> * 當我們意見不合時，我們會測試想法，讓數據來決定。

Make It Fun
* Our product is built on play, using gamification and design to make learning fun.
* Our brand is wholesome but unhinged: we lean into what makes our fans laugh, even if not everyone gets the joke.
* We design our offices and culture to be quirky and welcoming, sparking joy and connection among Duos.

> 讓一切充滿樂趣
> * 我們的產品建立在遊戲化的基礎上，透過設計讓學習變得有趣。
> * 我們的品牌是有益但瘋狂的：我們擁抱讓粉絲發笑的元素，即便不是所有人都能懂那個笑點。
> * 我們的辦公環境與文化充滿趣味與包容性，讓每一位 Duos 都能感受到歡樂與連結。

. . .

**The Green Machine** is our approach to building things:
* Staff it with great people
* Define success
* Set guardrails and think long-term
* Build the thing and set up feedback loops
* Execute with urgency and excellence
* Double down on what works, stop what doesn’t

> **綠色機器**是我們打造一切的方式：
> * 配備優秀人才
> * 定義成功
> * 設立規範，長遠思考
> * 建立，同時制定回饋機制
> * 以緊迫感與卓越執行任務
> * 強化有效策略，淘汰無效方案

### A Note Before Reading | 閱讀前的提醒
Duolingo is a product-led organization. But the ideas in this book aren’t just about building a great product—they’re about building a great company, together.

Not every section applies to every employee in every situation. Think of the principles simply as a guide to understanding how we work when we’re at our best.

> Duolingo 是一個產品主導的組織，但這本書的想說的不僅僅是關於如何打造一個好的產品，更是關於大家如何一起建立一個好公司。
>
> 並非每個章節都適用於每位員工或每個情境。請將這些原則視為一個簡單的指南，幫助你理解當我們發揮最佳狀態時，是如何運作的。


### Table of Contents 目錄
Table of Contents
Take the Long View
Raise the Bar
Ship It
Show Don’t Tell
Make It Fun
The Green Machine
Glossary

### PRINCIPLE #1 TAKE THE LONG VIEW | 原則 #1 長遠考量
If it helps in the short-term, but hurts Duolingo in the long-term, it’s not right.

> 如果短時間內有幫助，但會長遠的傷害 Duolingo，那就是不對的。

Duolingo was never going to be a sprint.

It wasn’t a quick experiment, or a weekend side hustle.

We knew that building the best education app in the world would be a multidecade effort—and that it would require patience. But patience—that is, taking the long view—is hard.

Take advertising. We could increase revenue tomorrow by showing more ads in the app. But we know that too many ads can annoy users and stifle long-term growth, potentially compromising our goal of making the best education universally available.

This is a real trade-off. But over and over, we’ve taken the long view. We have to: our goals are too big to think any other way.

> Duolingo 從來不是一場短跑衝刺
>
> Duolingo 不是一個短暫的實驗，也不是週末的副業。
> 
> 我們知道，打造一個全球最好的教育應用程式需要數十年的努力，這是一場耐力賽。而耐心——也就是長遠考量——並不容易。
> 
> 以廣告為例。如果我們在 app 裡放入更多廣告，明天的收益就能立刻增加。但我們也清楚，過多的廣告可能惹惱使用者，扼殺長期的成長，甚至會影響我們讓優質教育普及化的目標。這是一個嚴肅的取捨。但一次又一次，我們選擇了長遠的視角。我們有責任如此：我們的目標很宏大，無法用其他方式來達到。

In the Beginning

Not every company is able to operate like this. But we had a few early advantages that made taking the long view possible. For one, Luis had already sold his first company, reCAPTCHA, in 2009. As he put it: “This gave me the flexibility and perspective to think about our mission first and foremost.” So we set out to build something groundbreaking—the kind of educational tool our children and grandchildren might still be using. The clarity of this vision, along with the trust of our earliest investors, gave us leeway as we figured out what Duolingo could be. Equally important: we hired folks who were just as crazy about our mission. Back then, many of them could have doubled their salaries working at bigger tech companies. But they didn’t come here to make a quick buck—they came here to build the best learning tool on the planet.

> 剛開始時候
>
> 並不是每家公司都有能力這樣運作。我們在創立初期擁有幾個優勢，使我們能夠以長遠為考量。首先，Luis 在 2009 年時，出售了他的第一家公司 reCAPTCHA。他曾說過：「這給了我彈性與遠見，能思考我們的使命，並擺在第一優先。」
>
> 因此，我們立志打造一款開創性的產品——一個我們的子孫後代還會持續使用的教育工具。這個清晰的願景，加上最期投資人的信任，讓我們有餘裕去探索 Duolingo 的可能性。同樣重要的是，我們找來了一群對這個使命瘋狂的人。當時，如果他們選擇加入大型科技公司，薪資可能會翻倍。但他們來到這裡，放棄了快速致富，而想要打造世界上最棒的學習工具。

Don’t Do Dumb S**t

The temptation of short-term wins can be powerful. We had a simple mantra in the early days: “Don’t do dumb s**t.” Looking back, this was the first version of “Take the Long View.” We knew that to have any shot at meaningful success, we had to steer clear of gimmicks and tricks that might seem helpful in the short-term but hurt us down the road.

> 別做蠢事
> 短期成功的誘惑很強大。我們在創業初期有一句簡單的座右銘：「別做蠢事（Don’t do dumb s**t）。」回頭看，這其實就是「長遠考量」的最初版本。我們很清楚，如果想要真正的成功，就得避開那些看似短期內有用，但最終可能造成傷害的花招和小手段。
