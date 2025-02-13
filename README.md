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
> 對我們早期的大多數員工來說，Duolingo 是他們第一份正式的工作。我們沒有太多的經驗，得靠不斷嘗試來解決最基本的問題：我們應該聘請什麼樣的人？該怎麼打造一款優秀的 app？我們又該如何組織團隊來打造它？這樣的摸索花了不少時間，但到頭來，這正是塑造我們文化和成功的關鍵。
>
> 隨著時間推進，我們對這些問題的答案越來越清晰，還學到了更多新的經驗。如今，十四年過去了，我們決定把這些經驗整理成冊，清楚表達我們是如何做事的。
>
> 這本書的核心，是五大原則。它們並不是遙不可及的理想——而是我們親身經歷學到的寶貴經驗。但這些原則也並非一成不變，其中有矛盾、有取捨，甚至未必適用於所有情境。我們希望你能細讀它們、挑戰它們，然後幫助我們讓這本書的下個版本變得更好。
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
> * 我們正在打造一個永恆的產品，以長期使用者留存為首要目標。
> * 我們招募優秀的人才：能與 Duolingo 一同成長，並在未來數年塑造它的發展。
> * 我們正在建立一個百年品牌，以充滿趣味且獨特的角色，融入學習者的生活中。

Raise the Bar
* Every feature we ship must be intuitive, delightful, useful, and polished.
* We make sure critical tasks have a clear owner.
* We constantly dogfood our products to identify bugs and propose improvements.
* We give candid feedback that focuses on the “what” and not the “who.”

> 樹立標竿
> * 每項功能都必須直覺易用、充滿趣味、實用且精雕細琢。
> * 我們確保每項關鍵任務都有明確的負責人。
> * 我們親自體驗自家產品，發現問題並提出改進方案。
> * 我們給予坦誠的回饋，對事而不對人。

Ship It
* We optimize “clock speed,” minimizing gaps between steps to maintain momentum.
* We run hundreds of experiments each week in order to constantly improve our products and our organization.
* We ruthlessly prioritize projects with the highest impact and quickly cut what isn’t working.
* We’ll only introduce a new process if it helps us make faster, better decisions.

> 上線吧
> * 我們最佳化「時脈」，縮短各階段間的間隙，以保持動力。
> * 我們每週進行數百次實驗，持續改進產品與組織。
> * 我們毫不猶豫優先投入最具影響力的專案，並果斷淘汰無效方案。
> * 只有當新流程能幫助我們更快、更好的做出決定時，我們才會引入它。

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
> 並非每個章節都適用於每位員工或每個情境。請將這些原則視為一個簡單的指南，幫助你理解當我們發揮最佳狀態時是如何運作的。


### Table of Contents 目錄
* Take the Long View
* Raise the Bar
* Ship It
* Show Don’t Tell
* Make It Fun
* The Green Machine
* Glossary

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
> 以廣告為例。如果我們在 app 裡放入更多廣告，明天的收益就會立刻提升。但我們也清楚，過多的廣告可能惹惱使用者，扼殺長期的成長，甚至會影響我們讓優質教育普及化的目標。這是一個嚴肅的取捨。但一次又一次，我們選擇了長遠的視角。我們有責任如此：我們的目標很宏大，無法用其他方式來達到。

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

Betting on Technology

Taking the long view isn’t just about what you avoid— it’s also what you embrace. We are tech optimists. From the beginning, we’ve believed that technology will advance enough to make our most ambitious ideas possible. And betting on that has been crucial to how we operate. For example, we invested in early text-to- speech systems instead of recording human voices: even though our audio sounded robotic at first, we knew the technology would improve with time.

> 押注科技
> 
> 長遠考量不僅是關於你要避免什麼，也關於你要擁抱什麼。我們是科技樂觀主義者，從一開始，我們就相信科技會進步到足以實現我們的雄心壯志。押注於科技也成為了我們運作的關鍵。例如，我們早期投資了語音合成技術，而不是錄製真人語音，雖然剛開始我們的音訊聽起來很機械，但我們知道這項科技會不斷進步。

Long View Hiring

Hiring decisions are some of the most important decisions we make. That’s why we take time to find the right person — even if it means waiting. Each new hire needs to meet our bar. Is this person exceptional? Are they willing to get their hands dirty? Are they a clear communicator? Will they prioritize what’s best for the company over their personal goals?
We don’t compromise our hiring standards to fill a hole in the organization, especially when it comes to being a team player. As we say at Duolingo: “Better a hole than an a**hole.”

The good thing is, when you hire the right people, they tend
to stick around. And our experience validates this: on average, Duos stay here much longer than employees at most tech companies. Many are exceptional generalists who start with us as new college grads, develop their skills here, and take on new challenges over time. Whatever your experience level, we want you here for the long run.

> 長遠考量的招募
> 
> 招募決策是我們所做的最重要決策之一。這也是為什麼我們會花時間找對的人——即使這意味著等待。每位新進員工都必須符合我們的標準。這個人優秀嗎？他們願意捲起袖子親自動手嗎？他們能清楚的表達嗎？他們會將公司利益置於個人目標之上嗎？
> 
> 我們不會為了填補組織裡的空缺而降低招募標準，尤其是在尋找一起合作的成員。如同我們在 Duolingo 流傳的一句話：「寧可少個人，也不要有個爛人。」
> 
> 好消息是，當你找了對的人，他們往往會長期留在這裡。我們證實了這一點：平均來說，Duos 的在職時間比大多數科技公司的員工要長久。許多人從剛畢業的學生起步，在這裡發展他們的技能，隨著時間挑戰新的任務。無論你有多少經驗，我們都希望你能長期的在這裡。

Building a Forever Product

The Duolingo app is designed to be sticky in the short- term and transformative in the long-term. For years, we’ve focused on building something so useful and delightful that it becomes an essential part of our learners’ lives.
Learning—particularly language learning—requires regular practice over extended periods of time. That’s why we prioritize user retention, and have spent years perfecting the Streak feature. The more we can do to keep our learners committed for the long haul, the more value they’ll get from Duolingo.
We also invest in teaching better. Even though this doesn’t generate immediate revenue, we know that if a product fails to deliver on its promise, people will eventually stop using it.

> 打造永恆的產品
> Duolingo 的設計不僅要讓使用者在短期內愛不釋手，更要在長期帶來深遠的影響。多年來，我們專注於打造一個實用又令人愉悅的產品，讓它成為學習者生活中不可或缺的部分。
> 
> 學習——特別是語言學習——需要長時間的規律練習。因此，我們將使用者留存率視為優先目標，並投入多年時間打磨連勝（Streak）功能。我們做的越多，讓學習者持續投入越久，他們從 Duolingo 獲得的價值就越高。
> 
> 我們也不斷投資於更好的教學方式。雖然這不會立即帶來營收，但我們深知，如果產品無法兌現它的承諾，使用者最終還是會停止使用。

Notifications

Every day, Duolingo sends millions of messages to learners. These notifications present a fundamental tension between long-term thinking and short-term goals.
More notifications leads to more Daily Active Users (DAUs)*
in the short-term. But people who feel bombarded don’t stick around for long—they eventually turn off notifications or abandon the app entirely. That's why we put firm limits on notifications, regardless of what the short-term metrics suggest. User trust matters more than immediate gains.

> 通知機制
> 
> Duolingo 每天都會發送送數百萬則訊息給學習者，而這些通知必須在長遠考量與短期目標之間取得平衡。
> 
> 增加通知次數，短期內確實能提升每日活躍使用者數（DAU），但如果使用者覺得被訊息轟炸，最終不是關閉通知，就是直接刪除應用程式。因此，無論短期數據顯示什麼結果，我們都會嚴格控制通知的頻率。比起眼前的成長，我們更在乎的是使用者的信任。

Juicy

Duolingo didn’t always look like the app you see today. For years, it featured a light gray background, muted button colors, and a more robotic-looking Duo. But in 2018, a few of our designers and illustrators began working on a concept for a kids’ app. With brighter colors, rounder corners, and a cuter, friendlier Duo, the new design made learning feel more like a game. It was exactly the kind of playful experience we wanted for the main app. So, even though we didn’t expect it to boost metrics in the short- term, we took the leap and applied this new design language— dubbed Juicy—across all of Duolingo.

This redesign wasn’t just about aesthetics; it was an investment in the future. While risky and resource intensive, it set the foundation for the playful world that now defines our brand: expressive characters, delightful animations, and a learning experience that feels like play. By taking the long view, we created a design language that would scale with the product for years to come.

> Juicy
> 
> Duolingo app 一開始不是你現在看到的這種風格。早期的介面是淺灰色背景、低飽和度的按鈕，以及一隻機械感較重的 Duo。直到 2018 年，幾位設計師和插畫家開始為兒童版 app 構思新風格，更鮮豔的色彩、更圓潤的邊角，還有一隻更可愛、更親切的 Duo。這樣的設計讓學習變得更像遊戲，也正是我們想要帶給大家的體驗。因此，雖然我們不認為這養的改變在短期內能帶來數據的成長，但我們還是大膽採用了這種全新的設計語言，將其使用在整個 Duolingo 生態系，這就是 Juicy。
> 
> 這次改版不只是視覺上的調整，更是對未來的投資。雖然過程風險高、資源投入大，但它奠定了 Duolingo 充滿趣味性的品牌基調：生動的角色、俏皮的動畫，以及讓學習更像遊戲的體驗。從長遠來看，這套設計語言讓我們能夠隨著產品的發展不斷擴展，並保持一致的風格。

Setting the Proficiency Standard

When asked how much English somebody knows, we want them to say, “My Duolingo Score is 70.” The Duolingo Score is an estimate of users’ proficiency in the language they’re learning, and the Duolingo English Test (DET) is a way to certify the
score that can be used for high-stakes purposes, like university admissions. Together, they form our two-pronged approach to becoming the standard measure for language proficiency. Putting the score in the app gives us volume—hundreds of millions of people see it. Having a way to certify it with the DET gives us credibility—the score can get you admission to even the most prestigious universities in the world.
Of course, becoming the proficiency standard is not easy, and could take decades—but that’s exactly why the Duolingo Score and the DET are great examples of taking the long view.

> 設立語言能力標準
> 
> 當問起某人的英文程度如何，我們希望回答會是：「我的 Duolingo 分數是 70。」Duolingo 分數是對使用者正在學習的語言做的能力評估，而 Duolingo 英文測驗（DET） 則提供了一種正式認證方式，適用於大學申請等重要場合。這兩者結合，構成了我們建立語言能力標準的雙軌策略。
> 在 App 內顯示分數，能讓數億使用者看見它，這帶來了規模優勢。而透過 DET 認證，則讓這個分數具備公信力——甚至全球最頂尖的大學接受它作為語言能力證明。
> 當然，要成為語言能力的標準衡量指標並不容易，甚至可能花費數十年——Duolingo 分數與 DET 就是我們長遠考量的最佳例證。

Engineering the Future

In engineering, taking the long view requires a slightly different approach. We know that we will still be improving our products years from now. So, we don’t build systems to last forever. Instead, we test ideas quickly and only invest significant engineering resources when something is successful. If something doesn’t work, we move on quickly, keeping the codebase clean and minimizing waste.
Video Call is a great example. We only invested in scaling and stabilizing it for long-term use once it showed traction with users. Another example relates to notifications. When we realized we’d be testing notification copy for years to come, we built a custom tool that allows Product Managers to test copy without engineering support.
This balance—focusing on speed while reserving long-term investments for what truly works—has guided our success.

> 打造未來的工程
> 
> 在工程領域，長遠考量有略微不同的方式。我們知道在未來數年我們仍會不斷改進產品。因此，我們不會一開始就設計一個永久不變的系統，而是先快速測試想法，只有在成功驗證後，才投入大量工程資源。如果某項嘗試行不通，我們會果斷捨棄，保持程式碼乾淨，避免不必要的浪費。
> 視訊通話是一個很好的例子，我們只在它獲得使用者青睞後，才投入資源擴展與穩定系統。另一個例子是通知，當我們意識到未來幾年都會不斷測試通知文案時，便開發了一個專屬工具，讓產品經理可以自行測試文案，而不需要依賴工程團隊。
> 這種在速度與長期投資之間取得平衡的方式，讓我們能夠快速創新，同時確保真正有效的方案能夠長久發展，也正是我們成功的關鍵。

Becoming a Business

For years, Duolingo didn’t make money. We were laser-focused on growing our user base and keeping learners engaged. Also, some of us worried that monetizing Duolingo could get in the way of our mission.
That perspective began to shift after our Series D funding round in 2015. We started exploring revenue models—in-app purchases (IAPs), advertising, and paid subscriptions—with one key caveat: they could never compromise our mission. We weren’t going to put learning behind a paywall.

> 邁向商業化
> 
> 多年來，Duolingo 並沒有營利。我們將全部心力投入在擴大使用者群體，並確保學習者能持續參與。此外，我們中的一些人擔心，商業化可能會影響我們的使命。
> 這樣的想法在 2015 年 D 輪融資 後開始轉變。我們開始探索不同的營收模式——應用內購買（IAPs）、廣告與付費訂閱，但有一個關鍵原則：這些做法絕不能違背我們的使命。我們不會把學習鎖在付費牆後。

Building a Monetization Engine

We started with in-app purchases, but there wasn’t much to “buy” except a Streak Freeze. Advertising was also capped. We found that we could show one ad after each lesson without affecting user retention, but more than that would drive people away.
It became clear that introducing a freemium subscription product was the best opportunity to scale the business. The hard part was doing so while still offering an excellent product for those who couldn’t pay. We landed on a subscription package that eliminated ads and gave learners unlimited hearts. Both of these features remove friction from the app. Over the years, we’ve continued to tweak this model, but the core dynamic is the same: the paid product gives us the resources to pursue our mission at the greatest scale, and the free product is largely how that mission is achieved.
Plenty of investors—and even some of us at Duolingo —wondered whether offering such a great free product would provide too little incentive for learners to subscribe. There will likely always be a tension between accessibility and revenue. But over time, our approach to monetization has shown that we can strike this balance, achieving long-term loyalty while building a large business.

> 打造變現引擎
> 
> 我從應用程式內購著手，但除了連勝激凍（Streak Freeze）以外，幾乎沒什麼能買的。廣告收入也有限，我們發現每堂課結束後播放一則廣告不會影響使用者留存，但如果超過這個數量，大家就會選擇離開。
> 於是我們意識到，推出 Freemium 訂閱方案是擴展業務的絕佳機會。困難的是，如何讓無法負擔費用的使用者依然獲得優質的學習體驗。我們設計出訂閱方案，提供無廣告體驗，並解除愛心限制，這兩個功能減少了學習上的摩擦，讓學習流程更加順暢。多年來，我們不斷微調這個模式，但核心理念始終不變：付費產品讓我們有資源推動使命，而免費產品則是我們實現使命的關鍵。
> 許多投資人，甚至 Duolingo 團隊內部的一些人，曾經擔心如果免費內容做得太好，會導致使用者缺乏訂閱的動機。事實上，可及性與營收之間的拉扯可能永遠都會存在。但時間證明，我們的變現策略找到了平衡點，既建立了長期忠誠度，並發展出一個龐大的事業。

A 100-Year Brand

Through steady growth and clever marketing, we’ve made Duolingo a household name. Even people who’ve never used the app are familiar with our mascot, the delightful—if sometimes unhinged—Duo. We’ve invested a ton in Duo’s journey, along with the rest of our characters and the world they inhabit. This says a lot about our ambitions. We’re not just trying to help people get better at French. We want to build a brand and set of characters that become a part of people’s lives, turning everyone in the world into daily learners.

> 打造百年品牌
> 
> 透過穩健成長與巧妙行銷，Duolingo 已經成為家喻戶曉的品牌。即使從未使用過我們 App 的人，也對我們的吉祥物 Duo——一隻既可愛又偶爾有點失控的貓頭鷹——感到熟悉。我們投入大量心力塑造 Duo 的故事，以及他與其他角色所存在的世界，而這也反映了我們的遠大目標。
> 我們的不只是想幫助人們學好法語，我們想要打造一個深入人心的品牌與角色，讓學習成為每個人日常生活的一部分，讓世界上的每個人都成為終身學習者。

Characters Count

Our characters make learning fun. Built from simple geometric shapes, each has a distinct personality and story. Together, they reflect the diversity of our learners and bring a sense of humor and play to the app.
But these characters—inspired more by brands like Nintendo than traditional learning companies—also serve an important strategic purpose. We see this IP as a crucial moat for our business, especially in the era of AI learning tools. That same emotional connection that makes learning enjoyable also makes our product stickier over time. Even if someone cloned our entire app, learners would still come back to Duolingo for the characters.

> 角色的力量
> 
> 我們的角色讓學習變得有趣。這些角色由簡單的幾何形狀構成，但每個都有獨特的個性與故事。他們不僅展現了我們學習者的多樣性，也為 app 帶來了幽默與遊戲性。
> 這些角色的設計靈感更接近任天堂這類品牌，而非傳統的教育公司，從策略角度來看，這些角色是我們業務重要的護城河，特別是在 AI 學習工具迅速崛起的時代。與角色們建立了情感，不僅讓學習更愉快，也提升了產品的黏著度。即便有人複製了我們的 app，學習者仍然會回到 Duolingo，因為這些角色是無可取代的。

Investing in Marketing

At Duolingo, we’ve grown by creating a product that people genuinely love—and love to talk about. But we’ve also figured out how to use other levers, like performance marketing, to complement that organic growth. Our paid ads exist to amplify our word-of-mouth momentum, not replace it, so we are conservative with our spend. This allows us to invest in standout campaigns and reactive social moments that set us apart.
Our marketing team excels at creating high-impact content at a low cost. Thanks to their work, Duo has walked the red carpet at the Barbie premiere, hosted a (fake) dating reality show on the streaming service Peacock, and become an international social media star. These moments reflect the playful, irreverent energy of our brand and show how a thoughtful balance of organic growth and marketing can create meaningful impact.

> 投資行銷
> 
> 在 Duolingo，我們的成長來自於打造一款人們真正喜愛，並樂於分享的產品。但除了這種自然增長，我們也善用行銷策略來進一步擴大影響力。我們的付費廣告只是為了放大口碑效應，而不是取代它，因此我們在廣告預算上相當謹慎，將資源集中在 亮眼的行銷活動與即時社群操作上，以突顯品牌特色。
> 我們的行銷團隊擅長 以低成本創造高影響力 的內容。正因如此，Duo 曾在《芭比》電影首映會紅毯 上現身、在 Peacock 串流平台上推出一檔（惡搞的）戀愛實境秀，甚至成為全球社群媒體的熱門話題。這些時刻展現了 Duolingo 俏皮又不按牌理出牌的品牌個性，也證明了口碑行銷與精準行銷的完美平衡能帶來強大影響力。

The Path

Originally, learners navigated Duolingo through the Tree, which consisted of skills (e.g., going to a restaurant). Each skill began with basic word meanings and progressed to harder content, but learners only needed to complete the first level to move on. While this flexibility let them advance quickly, it often led to frustration when harder concepts came along and exposed gaps in their foundational knowledge.
In 2022, we took a leap: replacing the Tree with the Path. This new linear structure requires learners to complete every lesson in sequence, ensuring a consistent and strong foundation
for everyone. The Path was a large undertaking across both engineering and design. We anticipated that learners might resist such a dramatic change to their routine. And even though the data didn’t immediately show improvements in core metrics like DAUs or monetization, the switch was the right decision.
It prioritized real mastery over speedrunning easy lessons to maintain streaks. It also gave us clearer insights into learner progress and greater control over the learning experience.
Sometimes taking the long view means making bold moves that might seem counterproductive in the moment. The Path was just that. It fundamentally changed how people learn with Duolingo and has been essential to our success.

> 學習路徑
> 
> Duolingo 原本採用樹狀結構來安排學習進度，每個主題（例如「去餐廳」）都從基礎單字開始，逐步延伸到更進階的內容。不過，學習者只需要完成第一級，就能直接跳到下一個主題。雖然這種彈性讓人 進度推進快速，但當學習者遇到更難的概念時，卻容易發現基礎知識的漏洞，導致挫折感增加。
> 2022 年，我們做出了一個大膽決定：以線性路徑取代樹狀結構。 這種線性學習的方式讓所有學習者必須按照固定順序完成每一課，確保每個人都能打下穩固的語言基礎。這項改變牽涉到工程與設計團隊的全面調整，我們也預期學習者可能會抗拒如此劇烈的變動。事實上，短期內我們並未看 每日活躍使用者數或營收等核心指標的立即提升，但我們依然認為這是正確的決定。
> 
> 新架構的核心理念是優先培養真正的語言掌握能力，而非單純為了累積連續學習天數而快速通關簡單的課程，此外也讓我們更清楚掌握學習者的進度，能更精準的調整學習體驗。
> 
> 有時候，長遠佈局意味著在當下做出看似不利的決策。學習路徑就是一個典型例子——它徹底改變了人們使用 Duolingo 學習的方式，也成為我們成功的重要關鍵之一。

### PRINCIPLE #2 RAISE THE BAR | 原則 #2 樹立標竿

To change how the world learns, we must do world-class work.

> 要改變世界的學習方式，我們就必須做到世界級的水準。

Excellence isn’t some lofty goal—it’s our baseline.

The expectation is that we’ll do the best work of our careers here, constantly pushing our craft and ideas to meet our bar and then exceed it.
Still, we’re human, and we’re going to make mistakes. When that happens, we don’t chase blame. We dig in and figure out what happened. This is how we continuously raise the bar—not by being perfect, but by being a little bit better each day.

> 卓越不是一個崇高的理想——而是我們的基本要求。
> 
> 我們期望在這裡創造出職涯中最出色的成就，不斷推動我們的技藝和創意，不僅達到我們訂下的標準，更要超越它。
> 
> 然而，我們畢竟都是人，難免會犯錯。當錯誤發生時，我們不會到處追究責任，而會深入分析，找出問題所在。這就是我們不斷提升標準的方式——不在於追求完美，而是每天都進步一點。

Culture of Excellence

Our bar for quality was set at the top and at the beginning. Luis, Severin, and the early team share a nearly ridiculous attention to detail. (Luis is the rare CEO who still reports every bug he finds in the app.) But it’s no longer just about leadership or any individual Duo. As the company has grown, we’ve worked together to define clear standards for excellence and scale them across the organization.

> 卓越文化
> 
> 我們對品質的要求一開始就設立在最高點。Luis、Severin 和早期的團隊對細節的要求近乎到了苛刻的程度。（Luis 是那種至今仍會回報他在 app 中發現的每一個 bug 的難得 CEO。）卓越不是僅僅是領導層或某一位 Duo 的功勞，隨著公司成長，我們共同定訂了明確的卓越標準，並推廣到整個組織。

Taking Ownership

One key to maintaining high standards is assigning ownership. That means putting a person or team on a task, providing a clear mandate and saying, “You are responsible.” We’ve seen it again and again: only things that are owned become excellent.
As we grow, unclear ownership can become a challenge. One task might stretch across four functions and seven teams, and it’s not clear who owns what. There will always be some projects where defining ownership is tricky, or impossible. But the most important projects at the company should have an owner.

> 承擔責任
> 
> 維持高標準的關鍵之一，就是明確指派負責人。也就是說，將任務分派給某個人或團隊，賦予明確的指令，告知「這項工作由你負責。」我們屢次發現，只有那些有明確負責人的事情，才能達到卓越。
> 隨著組織的成長，責任的歸屬會是一大挑戰。一項任務可能需要橫跨四個部門和七個團隊，但究竟誰負責哪個部分卻不太明朗。總會有一些專案很難、甚至無法界定定責任。但公司中最重要的專案，一定要有明確的負責人。

Hard on the Work, Easy on the People

Our culture is famously warm and friendly. And that’s great! But a warm-and-fuzzy culture can make it hard to have tough conversations. We’ve always been clear when giving feedback on design and product, but we want to be more candid in other areas, too.
The standard here is “hard on the work, easy on the people.” That means giving constructive, clear feedback that sharpens ideas without undermining relationships. (We stick to the “what,” not the “who.”) It also means being open to receiving feedback and not taking it personally. This candid, constructive approach allows us to hold each other to high standards while fostering trust and collaboration.

> 對工作嚴格，對人寬容
> 
> 我們的文化以溫暖和友善聞名，這點非常棒！但是這種溫暖的文化，有時會讓我們難以展開嚴肅的對話。我們在給予設計和產品回饋時一向直截了當，對於其他領域，我們也希望能更加直接。
> 這裡的標準是「對工作嚴格，對人寬容」，這意味著我們提供有建設性、清楚的回饋來激盪想法，而不會破壞彼此的關係。（我們關注的是「事情」本身，而非「個人」。）這同時也代表，我們願意開放心胸接受意見，不把意見視為針對個人的批評。真誠、具建設性的建議，讓我們能夠在彼此督促達到高標準的同時，也能培養出信任與協作的氛圍。

Dogfooding

Another key way we maintain excellence is by using the app daily. This ensures that we ourselves love the product and that bugs are spotted and resolved quickly. To make this process
even more effective, we built Shake to Report, a simple tool that lets anyone in the company snapshot and report an issue instantly by shaking their device. Over the years, Shake to Report has become a vital part of our development process, making excellence in the app a shared responsibility.

> 親自使用
> 
> 另一個維持卓越的關鍵方式，就是每天使用我們的 app。這不僅確保我們自己也愛上這個產品，同時也能迅速發現並修復漏洞。為了讓這個過程更加有效，我們開發了「搖晃以回報問題」——一個簡單的工具，只需搖晃裝置，便能讓公司內任何人立即截圖並回報問題。多年來，「搖晃以回報問題」已成為我們開發流程中不可或缺的一環，使追求 app 卓越品質變成了大家共同的責任。

Setting the Bar

So, where exactly is this excellence bar, and how do we make sure we’re hitting it? Let’s see what this looks like across a few areas of the company.

The Bar for Product and Design

In product and design, there are four elements that guide us:
* Useful: Learners need to get utility out of whatever we’ve built. Otherwise, we’ve made something that adds more complexity to the app and distracts learners from what they’re here to do.
* Intuitive: Learners should be learning, not figuring out how to use the app. Every feature must be easy to use for everyone—it doesn’t matter whether they’re a 75-year- old in India using an Android or a 16-year-old in New York City on an iPhone. If a feature or screen requires explanation or additional context, it’s not right.
* Delightful: Every new feature needs to have some amount of fun and delight. We might not need the most elaborate animations in the first iteration of a feature, but there should always be a hint of the magic that learners love.
* Polished: This is what makes a feature feel complete. Tight visual design, perfect copy, and seamless interactions are the baseline. Nothing should feel clunky or inconsistent. For instance, we shouldn’t have both a Back button and an X button that do the same thing.

> 設立標竿
> 這個卓越標準究竟在哪裡？我們又該如何確保自己能達到它？讓我們來看看公司各領域的具體表現。
>
> 產品與設計的標準
> 在產品與設計方面，有四個要素指引著我們：
>
> 實用性：學習者需要能從我們所打造的產品中獲得實際價值，否則我們只是在增加 app 的複雜性，反而讓學習者偏離他們原本的目標。
>
> 直覺性：學習者是來學習的，而不是來摸索該如何使用app。每個功能必須對所有人來說都易於操作——無論是使用 Android 的印度 75 歲長者，還是拿著 iPhone 的紐約市 16 歲青少年。如果某個功能或畫面需要額外解釋或說明，那就不合適。
>
> 趣味性：每項新功能都應該帶有一些樂趣與驚喜。雖然在功能的最初初版本中不必追求最精緻的動畫，但總該帶有一絲讓學習者著迷的魔力。
> 
> 精緻度：這是讓一項功能顯得完整的關鍵。緊密的視覺設計、完美的文案與無縫的互動是基本要求，任何部分都不應該顯得突兀或不一致。例如，我們不應同時設置一個「返回」按鈕和一個功能相同的「X」按鈕。

The Bar for Hiring

Our people set the bar for everything else we do.
So, we insist on bringing in exceptional talent— individuals who stand out not just in their skills but in their character. That might mean someone who was at the top of their class, or the first from their family to graduate from college—but also is genuinely kind. To maintain this standard, Luis and Severin still approve every new hire.
We don’t lower this bar for anyone. For example, we once passed on a senior executive for a role we had been trying to fill for over a year because they weren’t kind. They aced their interviews and had a strong resume but were disrespectful to the driver who picked them up from the airport. That single moment told us what we needed to know. Excellence isn’t just what you do—it’s how you treat others.

> 招募標準
> 
> 我們的團隊成員訂下工作中所有的標準。
> 因此，我們堅持聘用那些傑出的人才——不僅在技能上脫穎而出，更在品格上出眾。這可能意味著某人是班上的第一名，或是他們家中第一位大學畢業生，但最重要的是，他們必須是真誠且友善的人。為了維持這個標準，Luis 和 Severin 至今仍親自審核每一位新進員工。
> 我們絕不會為任何人降低這一標準。例如，我們曾因一位資深主管缺乏善意而放棄聘用，儘管這個職位我們已徵才超過一年。該主管在面試中表現出色，履歷也十分亮眼，但他對接機司機表現出不尊重的態度。僅憑這一刻，我們就得知他不符合我們的要求。卓越不僅在於你做了什麼，更在於你如何對待他人。

V1s Not MVPs

The idea of shipping unfinished features, or Minimum Viable Products (MVPs), is common across tech. But MVPs come with a specific set of expectations—and limitations.
At Duolingo, we don’t do MVPs—we do V1s.
The difference is important: MVPs often have a lower standard of quality and can be used as an excuse to ship subpar work. V1s, on the other hand, are polished. They may not have all the bells and whistles, but they meet our bar. Sometimes this approach takes a little longer, but we refuse to compromise our users’ experience by showing them half-baked ideas.

> 推出第一版，而非最小可行產品
> 
> 在科技界，推出未完成的功能或最小可行產品（MVP）的概念相當普遍，但最小可行產品帶有一系列特定的預期與限制。
> 在 Duolingo，我們不做最小可行產品，我們做第一版產品。
> 這一差異至關重要：最小可行產品往往代表較低的品質標準，甚至可能成為推出次等產品的藉口；而第一版產品則經過精心打磨。雖然它們可能不具備所有花俏功能，但完全符合我們的標準。有時這種作法可能需要更長的時間，但我們絕不會為了趕時間而以半成品的概念妥協使用者體驗。


### PRINCIPLE #3 SHIT IT! | 上線吧！
For a good idea to become reality, we need to move with a sense of urgency. So Go, Go, Go!
> 要讓好點子成真，我們必須以緊迫感行動。所以，快、快、快！

When Duolingo was starting out, we were all sitting in one room.
We didn’t have formal Product Reviews, or OKRs, or any of the structure we have today. There was no blueprint because no other learning app was doing what we were trying to do. We were—for better or worse—making things up as we went along.
We were also fast as hell. And the pace of our experimentation allowed us to quickly figure out what was working, and ditch what wasn’t. This applied across everything: product, hiring, engineering, and our business as a whole. We were testing and learning at warp speed.

It’s still like this even today. We ship new versions of our iOS and Android apps every week. And we’re running hundreds of experiments* across the company at any given time. Duolingo goes nowhere without this principle. “Ship It” keeps us ahead of our competitors; “Ship It” makes Duolingo a fun place to work; “Ship It” ensures that our product never sits still.

Go, Go, Go!

Duolingo is the sum of thousands of experiments. The faster we can run experiments—successful or not—the faster we can improve the app and advance our mission. Over time, each of these changes builds on one another, creating a cycle of compounding growth.
Shipping fast also lets us avoid lengthy debates and guesswork about what we should be doing. That’s because testing in the real world gives us better information than any internal discussion ever could. So, we move quickly—to start these feedback loops and let real data guide our work.

> 當 Duolingo 剛起步時，我們全都在同一間個空間裡工作。
> 當時我們沒有正式的產品檢討會、OKR，也沒有今天這些制度化的架構。因為沒哪個學習 app 和像我們想要做的類似，所以完全沒有可以參考的藍圖。我們只能不論成敗，邊走邊摸索。
> 我們真的快得不得了。高速的實驗節奏讓我們能迅速找出哪些方法有效，哪些無效，並及時捨棄不行的部分。這原則適用於所有領域：產品、招募、工程，乃至整個業務。我們以超高速不斷測試與學習。
>
> 即便到了今天，情況依舊如此。
> 我們每週都會發佈新版的 iOS 和 Android 應用程式，而公司內隨時都有數百個實驗在進行。沒有這個原則，Duolingo 絕不可能有今天的成就。「上線吧！」讓我們領先於競爭對手；「上線吧！」讓 Duolingo 成為一個有趣的工作環境；「上線吧！」確保我們的產品不會停滯。
>
> 快、快、快！
> 
> Duolingo 是由數以千計的實驗累積而成。我們進行實驗的速度（無論成敗）越快，應用程式的改進和我們使命的推進也就越迅速。隨著時間的推移，每一次改變都在累積，形成一個滾雪球式的成長循環。
> 快速上線還能避免我們陷入冗長的辯論和無謂的猜測，因為在真實世界中測試所得到的資訊，比任何內部討論都來得真實可靠。所以，我們必須迅速行動，啟動這些回饋循環，讓真實數據指引我們前進。

Clock Speed
“Clock speed” is a mindset that drives how we work. The concept comes from microprocessor technology, where clock speed measures how quickly a system can process instructions. We use the term to talk about minimizing the gaps between actions: the time between when a decision is made and when it’s implemented, or when feedback is given and changes are made.

Experiments: Experiments are tests to see what works and what doesn’t. A/B tests are a specific type of experiment where we simultaneously run two or more options against one another.

Increasing clock speed helps us reduce idle time and make sure that the most important projects actually get done. We should almost never have to wait a month to see the next iteration of a project. The more we can close these gaps, the faster we ship it, and the faster we can learn and improve. It’s not about rushing—it’s about never letting a break in the chain slow us down.

Ruthless Prioritization
As much as we want to move fast and increase clock speed, we always need to make sure we’re working
on the right thing. At Duolingo, prioritization is sometimes described as “ruthless:” we are decisive about what we focus on as a company, based on what will have the largest impact on our learners.
Deciding what to prioritize starts with clearly defined goals. For every initiative, we ask: How does this contribute to our mission? What measurable outcomes will it drive? And if something doesn’t move the needle in a meaningful way, it’s cut—no matter how much effort has already gone into it. One high-impact win always outweighs a handful of small scattered efforts.

*PR: Product Review. The meeting where we green-light every change to the app. Led by the Product Org, but anyone can listen in!

This mindset extends to our product. We cut features that don’t deliver value, remove unnecessary complexity, and stay laser- focused on our mission. Letting go of what’s not effective is often as powerful as creating something new.

*Shipping the Org
As teams grow and become more specialized, there’s a risk that our product will mirror the organization’s structure rather than delivering a seamless experience for learners. This
is called “shipping the org.” For example, the tabs across the app—like Leaderboards and Profile—are managed by different teams, each with distinct goals. Over time, this has led to inconsistencies in their design. To counter this, we always need to consider the holistic experience across the app.

Culture of Experimentation
“Ship It” isn’t just about speed; it’s about creating
as many opportunities as possible to learn and improve. We like to play around, run a little wild—and sometimes fail. But each experiment brings us closer to seeing what works.
99 Bad Ideas
Some of our best features and campaigns have come from asking ridiculous, unlikely questions. We practice this at leadership offsites during a tradition we call “99 Bad Ideas,” where we brainstorm outrageous concepts—like Duo’s latest hijinks, or changing our stock ticker to LILY.
But this spirit extends across the organization,
where we make space for challenging assumptions and asking bold questions. What if you could talk with Duolingo characters? What would Duo do with five seconds at the Super Bowl? What if language certification tests could be taken at home? Over
the years, these types of questions have helped us consistently uncover new opportunities to delight our learners and advance our mission.

* Navigating Trade-offs
There’s a natural tension between “Raise the Bar” and “Ship It.” When they clash, our mission is a great guide. The question is: How will this decision improve education and make it more accessible? Often, it means letting go of perfection. Generative AI, for example, lets us create content at a speed and scale we never thought possible. Early versions aren’t perfect, but they deliver value to millions now—and the quality will improve over time.

The Right Amount of Process
As Duolingo grows, staying agile becomes more challenging. We need guardrails and processes to keep things from spiraling out of control, but we also want to avoid unnecessary red tape. The question is: How can we add the right processes without slowing ourselves down?
Good processes should reduce workloads, improve quality, and lead to better decisions. One example of this is Product Review (PR). In the early days, Luis often made product decisions
during informal meetings, which sometimes got messy. Not all stakeholders were included or informed; even worse, it wasn’t always clear if decisions were binding or if Luis was just musing. We needed a better approach.
Taking inspiration from engineering’s code review process, we introduced a formal structure for Product Review. Today, PR ensures that everyone is clear on what decisions were made, and that all relevant stakeholders are informed. The meeting also includes a rotating group of leaders from Product and Design who weigh in, ensuring diverse perspectives.
The success of PR has set a precedent for other teams. Marketing, for instance, has adopted a Marketing Review, which brings the same clarity and alignment to their campaigns. These processes help us maintain our quality bar—and make faster and visible decisions across the company.

（以下尚未翻譯）
PRINCIPLE #4 SHOW DON'T TELL
We use clear, concise communication that is grounded in data and real impact.

“Show Don’t Tell” means we lead with the results of our work, not the story of its effort.
This approach is different from how most of us were taught. In school or past jobs, we often learned to communicate to persuade—selling ourselves with pitches and stories. While those skills have their place, they’re not how we uncover the truth, solve problems, or build great things.

Numbers Are the Story
Metrics, when available, should be at the center of all our work and communications. Decisions must be grounded in evidence, not abstract narratives.
By focusing on actual results—like the effect of a new feature on daily bookings—we can quickly assess whether something belongs in the app. But this spirit extends well beyond the app. For example, we measure how our offices are being used (and not used), so we can make each new space better than the last.
TL;DR
One key way we Show Don’t Tell is through TL;DRs—executive summaries at the top of any important communication. We use them in many places, from feature performance analyses and meeting prereads to new policy announcements.
Crafting strong TL;DRs boosts the chances that your work will be seen and remembered. They make complex information more digestible and, importantly, encourage clearer thinking. To write a TL;DR, you have to distill your message down to its most essential points.

*The Tyranny of Metrics
Fixating on the numbers can sometimes lead us astray. Metrics are valuable, but in isolation, they paint an incomplete picture. For example, learning outcomes—that is, what a student should know after completing a lesson—are notoriously tricky to measure. In cases like these, we have to trust our intuition and expertise.

Say Less
Prototypes, Not Pitch Decks
Talking about ideas is rarely as effective as building them. Prototypes allow us to bring concepts to life, align on a shared vision, and move forward quickly. They’re especially important when dealing with complex challenges like integrating AI into an existing feature.
Great Products Don’t Have to Explain Themselves
Our app is designed to be intuitive. Instead of telling learners how to use Duolingo with pop-over messages and lengthy onboarding flows, we let design, animation, and simple prompts do the “showing.” When you open up Duolingo for the first (or hundredth) time, the learning experience should require no instructions. That way, you can actually focus on learning.

And the actual learning is shaped by this principle, too. Research shows that the most effective learning comes through experience, not a long list of instructions. Rather than explaining grammar rules, for example, we demonstrate language patterns through interactive exercises and engaging visuals.
Ideas Before Egos
Great ideas don’t need a sales pitch—they need a chance
to prove themselves. At Duolingo, we prioritize results over opinions. By empowering teams to explore bold concepts and letting metrics guide the way, we ensure that the best ideas rise to the top.

*Celebrating Innovators
We tend to be team first. But there are select moments when individual work that goes above and beyond must be celebrated. Each year at Duoversary, we pick out a few standout contributors and give them the Duolingo Innovation Award.

Disagree and Commit
Disagreements are inevitable, but here, we handle them by taking action instead of getting stuck. When two parties disagree, both commit to moving forward with a decision and letting the results speak for themselves. For example, even when someone like Luis has doubts about an idea, they’ll often say, “Go ahead and test it—let’s see what happens.” (This is exactly what occurred with Leaderboards—now a key feature on the app.)
This mindset extends beyond product. On our social media team, for example, junior team members are trusted to run with bold ideas and measure their impact. By creating space for experimentation, we ensure that outcomes—not opinions—lead the way.
The Trust Battery
Building trust is an essential part of this approach.
At Duolingo, trust isn’t assumed—it’s earned. Through impactful work, everyone powers their Trust Battery. Whether you’re an intern or a new executive, you
start by demonstrating your value with meaningful contributions. Each contribution charges the
battery, creating a reserve of trust that strengthens collaboration, decision-making, and accountability over time.

PRINCIPLE #5 MAKE IT FUN!
We bring a sense of humor, joy, and imagination to everything we do.
Learning doesn’t have to be boring, and neither does work.
There’s a palpable sense of humor when you enter the world of Duolingo. This isn’t a culture of poker faces and formalities. It’s a world where gigantic, plush owls star in fake Broadway musicals—on ice. Where any wild idea is on the table, like an April Fools campaign to sell language-learning toilet paper. Where no one is safe from the joke (not even the CEO).

A Product Built on Play
There are lots of ways to teach a language. But none of them work if learners aren’t engaged.
From the beginning, we made the decision to gamify the app. Over time, we’ve expanded this by introducing more and more engagement mechanics that keep learners coming back to further their progress. But these tactics aren’t the only thing that sets us apart.
Duolingo feels like an entirely different universe from traditional education tools. Strange, unexpected things happen here. Lessons are formatted like talk shows and video games; sentences like “Your bear is drinking beer” verge on the absurd, and the character Lily sarcastically supports your progress with a slow clap. These moments of delight—characters, animations, absurd surprises—do more than entertain; they play a key role in keeping learners engaged.
You Can Be More Than One Thing
Duolingo doesn’t fit neatly into one category. We’re not a game, but we’re not just an education product either. Along that blurry line lies the magic. The fact is, we’re competing with platforms like TikTok, Instagram, and online games for attention, so we have to make learning as fun as any of them. These platforms are designed to keep people endlessly scrolling and watching. What sets Duolingo apart is that our users come with a clear goal: learning. It’s not mindless entertainment; it’s a productive and purposeful use of your time. And the fun, the unexpected moments, and the quirky design are what make you stay.

Quirky Culture Open Doors
At some companies, there is a room at the end of the hall with a giant mahogany table where all the real decisions are made. It’s not like that here. (In fact, Luis’s go-to conference room is a public fishbowl.) We’re open about the most important issues at the company—even ones that other places might try to keep quiet. Q&A with Luis is one space where this transparency is obvious. But more generally across Duolingo, we make a point of being available: even our most senior leaders are one DM away. Anyone at the company can attend Product Review. This openness and transparency set the conditions for taking risks and getting weird.
Joy by Design
Our product is fun because of the people who build it. It’s obvious to anyone who walks into the office:
on any given day, you might see a human-size Duo practicing calisthenics in the atrium, or stumble upon one of more than 100 clubs devoted to everything from crossword puzzles to oysters. Maybe you’re around in October and catch the annual Pittsburgh Puppy Parade. None of this is by accident. A great culture is hard to build, easy to lose, and essential for our success.

This reaches a peak during our annual winter Getaway, when the entire company decamps to Cancun without agendas or panels or training sessions. The goal is simple: give Duos a low-pressure space to connect and unwind. We believe that when we genuinely enjoy our working environment and each other’s company, work becomes better, in all senses of the word.

*Respect Boundaries
The reason we can be goofy and experiment without judgment is because we have a baseline of care and respect within the company. With a diverse team of backgrounds, experiences, and perspectives, it’s important to be thoughtful—what’s funny to one person might not land for another. Everyone here is an adult, and we expect you to respect people’s boundaries.

Wholesome and Unhinged
Over the years, we've experimented with different formats, tones, and design languages—eventually landing on our unique brand: wholesome and unhinged.
Committing to the Bit
It took some time to find our voice, especially with our external marketing. Early on, we tried to appeal to the broadest possible audience, but we ended up with nothing distinctive to say. And in marketing, there’s nothing worse than being bland. So we changed tack, and our approach to marketing became weird, unexpected, and often funny.
Humor doesn’t scale perfectly. It’s subjective, sometimes polarizing. So to unleash the full power of Duo humor, we had to accept that not everyone would get the joke. What truly matters is that people who do get it love it—and we do everything we can to nurture that passion.
Duality of Duo
Our mascot was initially designed to encourage regular practice. But once the internet got their hands on him, he grew into a more complicated—even menacing—character with his own lore. He’s still cute and cuddly. But he’s also willing to temporarily relocate your family to ensure you finish your lessons.

By leaning into the joke, Duo has become a bona fide viral sensation. He’s shown up everywhere from Saturday Night Live to popular video games and celebrity Instagrams. There are galaxies of crazy memes, from Buff Duo to Anime Duo and more.
April Fools
April Fools is the perfect holiday for Duolingo: everything is
fair game for a joke, and the further you push it, the better. We realized in the early years of the company that April Fools stunts were a great way to generate buzz and celebrate our quirky sense of humor. Our earliest experiments, like the Duolingo Pillow, have evolved into full-scale campaigns—like 2024’s Duolingo on Ice, which garnered 100 million social media impressions.

Five Seconds with Duo
Super Bowl LVIII. 200 million viewers are watching around the world. All of a sudden, a bright green owl shoots another owl out of his butt, reminding you to "Do your Duolingo."
It wasn’t your typical Super Bowl ad—but it couldn’t have been more Duolingo.
Those five seconds, which aired on February 11, 2024, were the culmination of months of collaboration across a half dozen teams. We didn’t want to pay for a 30-second spot, so we gave ourselves a challenge: How could we make a splash in just five? We knew that every pixel mattered. There wasn’t time for flash or filler, so we embraced the quirky, unhinged, unexpected nature of Duo himself. When debates broke out over the “right amount of butt” to show, we knew we had a winning idea.
The gamble paid off. For a fraction of the cost, our ad generated as much buzz as any other Super Bowl ad that year, and appeared on multiple “best of” lists. It was playful, unexpected, and didn’t take itself too seriously—exactly the formula that has driven our success as a brand.

THE GREEN MACHINE
Our principles provide the theory. The Green Machine puts that theory into practice.

Our Process
By this point, we’ve covered a lot about our principles—their history, why we have them, and what they mean. The Green Machine is a framework for putting them to work.
This approach emerged organically during our earliest days as a startup and has been refined every year since. (Along the way, it has produced some of our most valuable innovations and biggest wins.) You can think of The Green Machine as a process of continuous improvement through small changes. When a small change improves metrics, we make more changes like that.
In its most basic form, the Green Machine goes like this: gather excellent people, give them space to experiment, and then double down on what works.
If you're working on something, and you're stuck, check it against these six steps. Maybe it's faltering because you didn't think carefully enough about your team, or because you don’t have the proper feedback loops. The Green Machine model can help just about any project get on track.

The Green Machine: Six Steps 1. Staff It with Great People
Great experiments require exceptional teams who can quickly brainstorm ideas, execute, and pivot on a dime. This is why we set such a high bar in hiring and invest so much in our people. We like to keep teams lean and scrappy to start, only adding more people once we see success.
2. Define Success
We always want to set clear, measurable goals—whether it’s DAUs, bookings, or social impressions. But metrics aren’t always available for early-stage projects. In that case, we define the best available qualitative goals, iterate toward clarity, and keep an eye out for any useful signals.
3. Set Guardrails and Think Long-Term
We use guardrails to ensure our work benefits both Duolingo and our learners over the long term. This aligns with our core principle, Take the Long View. Thoughtful guardrails help us focus on sustainable, meaningful growth, ensuring that each experiment serves a greater purpose.

4. Build the Thing and Set Up Feedback Loops
The fastest way to create something excellent isn’t through abstract discussions. Just start building, and create the right continuous feedback loops. This feedback comes from both quantitative (A/B test results, social impressions, efficacy research) and qualitative sources (extensive dogfooding). Early- stage projects typically lean more heavily on qualitative feedback before shifting to more data-driven metrics.
5. Execute with Urgency and Excellence
Because of the compounding nature of smaller improvements, there is a huge cost to moving slowly. But moving too fast
can also lead to sloppy outcomes. In step five, we work to continuously (and urgently) ship work that meets our bar.
6. Double Down on What Works, Stop What Doesn’t
When something is working, we allocate more resources and keep working on it (sometimes for years). But we need to be comfortable sunsetting projects or even entire products that don’t demonstrate success.

Part of the Plan
Crucially, the Green Machine is not a replacement for planning. We still have quarterly OKRs, annual goals, and a long-range financial plan. The difference is that we don’t rely on multi-year roadmaps for the app.

Glossary
Bookings
We use bookings to indicate the amount of money we earn from users on subscriptions to Duolingo, in-app purchases, DET purchases, and advertising networks.
DAUs
Daily Active Users. The number of individuals using Duolingo every day across iOS, Android, and the website. DAUs is one of the most important metrics we track, and tells us how well our products are doing.
DET
The Duolingo English Test—our second major product. An adaptive certification test used to demonstrate English proficiency. Used primarily to meet international admissions requirements for universities.
Dogfooding
When Duos test features of the product themselves.
Duo
Duo was created in a
Duoversary
Once a year, we gather the entire company in Pittsburgh to celebrate the anniversary of launching Duolingo to the public: June 19, 2012.
Experiments
Tests to see what works and what doesn’t. A/B tests are a specific type of experiment where we simultaneously run two or more options against one another.
Go, Go, Go!
Something Luis yells when you’re doing something right.

Juicy
Duolingo’s visual design system. Plumper, friendlier, and juicier than it used to be.
MAUs
Monthly Active Users. Number of unique users who engage with Duolingo every month.
Nuo
Brilliant, bright-eyed owl who asks a ton of questions in their first 90 days of working at Duolingo.
OKRs
Objectives and Key Results. A model for goal-setting originally developed at Intel in the 1970s. Here at Duolingo, we set team OKRs every quarter and company OKRs once a year.
Parliament
A gathering of owls. Also, our weekly all-hands meeting—usually on Mondays.
Pittsburgh
Fabled city at the confluence of three rivers said to be the birthplace of Duo. Also, our HQ!
PR
Product Review—the meeting where we green-light every change to the app. Led by the Product Org, but anyone can listen in! (Alternative meanings: Public Relations, and Pull Request.)
SLT
The Senior Leadership Team—consisting of all VPs and above at the company. And a few stray owls.
Subscribers
Users who pay for access to any Duolingo paid subscription offering.
