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
> * 每項功能都必須直覺易用、令人愉悅、實用且精雕細琢。
> * 我們確保每項關鍵任務都有明確的負責人。
> * 我們親自體驗自家產品，發現問題並提出改進方案。
> * 我們給予坦誠的回饋，對事而不對人。

Ship It
* We optimize “clock speed,” minimizing gaps between steps to maintain momentum.
* We run hundreds of experiments each week in order to constantly improve our products and our organization.
* We ruthlessly prioritize projects with the highest impact and quickly cut what isn’t working.
* We’ll only introduce a new process if it helps us make faster, better decisions.

> 快速執行
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

（以下尚未翻譯）
Setting the Proficiency Standard

When asked how much English somebody knows, we want them to say, “My Duolingo Score is 70.” The Duolingo Score is an estimate of users’ proficiency in the language they’re learning, and the Duolingo English Test (DET) is a way to certify the
score that can be used for high-stakes purposes, like university admissions. Together, they form our two-pronged approach to becoming the standard measure for language proficiency. Putting the score in the app gives us volume—hundreds of millions of people see it. Having a way to certify it with the DET gives us credibility—the score can get you admission to even the most prestigious universities in the world.
Of course, becoming the proficiency standard is not easy, and could take decades—but that’s exactly why the Duolingo Score and the DET are great examples of taking the long view.

> 樹立語言能力標準
> 
> 當問起某人的英文程度如何，我們希望回答會是：「我的 Duolingo 分數是 70。」Duolingo 分數是對使用者正在學習的語言做的能力評估，而 Duolingo 英文測驗（DET） 則提供了一種正式認證方式，適用於大學申請等重要場合。這兩者結合，構成了我們建立語言能力標準的雙軌策略。
> 
> 在 App 內顯示分數，能讓數億使用者看見它，這帶來了規模優勢。而透過 DET 認證，則讓這個分數具備公信力——甚至全球最頂尖的大學接受它作為語言能力證明。
> 
> 當然，要成為語言能力的標準衡量指標並不容易，甚至可能花費數十年——Duolingo 分數與 DET 就是我們長遠考量的最佳例證。

（以下尚未翻譯）
Engineering the Future

In engineering, taking the long view requires a slightly
different approach. We know that we will still be improving
our products years from now. So, we don’t build systems to
last forever. Instead, we test ideas quickly and only invest significant engineering resources when something is successful. If something doesn’t work, we move on quickly, keeping the codebase clean and minimizing waste.
Video Call is a great example. We only invested in scaling and stabilizing it for long-term use once it showed traction with users. Another example relates to notifications. When we realized we’d be testing notification copy for years to come, we built a custom tool that allows Product Managers to test copy without engineering support.
This balance—focusing on speed while reserving long-term investments for what truly works—has guided our success.

Becoming a Business
For years, Duolingo didn’t make money. We were laser-focused on growing our user base and keeping learners engaged. Also, some of us worried that monetizing Duolingo could get in the way of our mission.
That perspective began to shift after our Series D funding round in 2015. We started exploring revenue models—in-app purchases (IAPs), advertising, and paid subscriptions—with one key caveat: they could never compromise our mission. We weren’t going to put learning behind a paywall.

Building a Monetization Engine

We started with in-app purchases, but there wasn’t much to “buy” except a Streak Freeze. Advertising was also capped. We found that we could show one ad after each lesson without affecting user retention, but more than that would drive people away.
It became clear that introducing a freemium subscription product was the best opportunity to scale the business. The hard part was doing so while still offering an excellent product for those who couldn’t pay. We landed on a subscription package that eliminated ads and gave learners unlimited hearts. Both of these features remove friction from the app. Over the years, we’ve continued to tweak this model, but the core dynamic is the same: the paid product gives us the resources to pursue our mission at the greatest scale, and the free product is largely how that mission is achieved.
Plenty of investors—and even some of us at Duolingo —wondered whether offering such a great free product would provide too little incentive for learners to subscribe. There will likely always be a tension between accessibility and revenue. But over time, our approach to monetization has shown that we can strike this balance, achieving long-term loyalty while building a large business.

A 100-Year Brand
Through steady growth and clever marketing, we’ve made Duolingo a household name. Even people who’ve never used the app are familiar with our mascot, the delightful—if sometimes unhinged—Duo. We’ve invested a ton in Duo’s journey, along with the rest of our characters and the world they inhabit. This says a lot about our ambitions. We’re not just trying to help people get better at French. We want to build a brand and set of characters that become a part of people’s lives, turning everyone in the world into daily learners.

Characters Count
Our characters make learning fun. Built from simple geometric shapes, each has a distinct personality and story. Together, they reflect the diversity of our learners and bring a sense of humor and play to the app.
But these characters—inspired more by brands like Nintendo than traditional learning companies—also serve an important strategic purpose. We see this IP as a crucial moat for our business, especially in the era of AI learning tools. That same emotional connection that makes learning enjoyable also makes our product stickier over time. Even if someone cloned our entire app, learners would still come back to Duolingo for the characters.

Investing in Marketing
At Duolingo, we’ve grown by creating a product that people genuinely love—and love to talk about. But we’ve also figured out how to use other levers, like performance marketing, to complement that organic growth. Our paid ads exist to amplify our word-of-mouth momentum, not replace it, so we are conservative with our spend. This allows us to invest in standout campaigns and reactive social moments that set us apart.
Our marketing team excels at creating high-impact content at a low cost. Thanks to their work, Duo has walked the red carpet at the Barbie premiere, hosted a (fake) dating reality show on the streaming service Peacock, and become an international social media star. These moments reflect the playful, irreverent energy of our brand and show how a thoughtful balance of organic growth and marketing can create meaningful impact.

The Path
Originally, learners navigated Duolingo through the Tree, which consisted of skills (e.g., going to a restaurant). Each skill began with basic word meanings and progressed to harder content, but learners only needed to complete the first level to move on. While this flexibility let them advance quickly, it often led to frustration when harder concepts came along and exposed gaps in their foundational knowledge.
In 2022, we took a leap: replacing the Tree with the Path. This new linear structure requires learners to complete every lesson in sequence, ensuring a consistent and strong foundation
for everyone. The Path was a large undertaking across both engineering and design. We anticipated that learners might resist such a dramatic change to their routine. And even though the data didn’t immediately show improvements in core metrics like DAUs or monetization, the switch was the right decision.
It prioritized real mastery over speedrunning easy lessons to maintain streaks. It also gave us clearer insights into learner progress and greater control over the learning experience.
Sometimes taking the long view means making bold moves that might seem counterproductive in the moment. The Path was just that. It fundamentally changed how people learn with Duolingo and has been essential to our success.
