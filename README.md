# The-Duolingo-Handbook-zh-TW
The Duolingo Handbook 正體中文翻譯

這是個人興趣所做的翻譯，未盡之處還請見諒。
版權為 Duolingo 所有。

## The Duolingo Handbook
How Duolingo works: 14 years of big learnings in one little handbook.

Duolingo 手冊

多鄰國怎麼做到的：14年的學習濃縮於一本小手冊

<img src="https://github.com/goescat/The-Duolingo-Handbook-zh-TW/blob/main/image/The_Duolingo_Handbook-01.png" width="400">

官方連結：
https://blog.duolingo.com/handbook/

## 內容

### 來自 Luis 的信

Duolingo 是個奇特的地方。

我們的文化不是照搬某家科技新創公司的成功範本，而是由一群宅宅，在美國賓州匹茲堡一家運動酒吧樓上的辦公室裡，從零開始打造出來的。

對我們早期的大多數員工來說，Duolingo 是他們第一份正式的工作。我們沒有太多的經驗，得靠不斷嘗試來解決最基本的問題：我們應該聘請什麼樣的人？該怎麼打造一款優秀的 app？我們又該如何組織團隊來打造它？這樣的摸索花了不少時間，但到頭來，這正是塑造我們文化和成功的關鍵。

隨著時間推進，我們對這些問題的答案越來越清晰，還學到了其他更多的經驗。十四年過去了，我們決定把這些經驗整理成冊，清楚表達我們如何做事。

這本書的核心，是五大原則。它們並不是遙不可及的理想——而是我們親身經歷學到的寶貴經驗。但這些原則也並非一成不變，其中有矛盾、有取捨，甚至未必適用於所有情境。我們希望你能細讀它們、挑戰它們，然後幫助我們讓這本書的下個版本變得更好。

感謝你的閱讀。
歡迎來到 Duolingo。

— Luis

> ### Letter from Luis
> 
> Duolingo is a quirky place.
> 
> Our culture wasn’t copied from a tech startup playbook. It was built from scratch by a few dozen nerds in an office above a sports bar in Pittsburgh, Pennsylvania.
> 
> For most of our early employees, Duolingo was their first real job. Without much experience, we had to experiment our way through the basic questions: Who should we hire? What’s the best way to build an app? How should we organize ourselves to build it? Doing it this way took time. But in the end, nothing could have been better for our culture and success.
> 
> Over time, we’ve sharpened our answers to these questions and many more. Now, fourteen years in, we’ve decided to put these answers into writing, and articulate how we do things.
> 
> At the center of this book are five principles. These aren’t aspirational—they’re lessons we've learned through experience. But they’re also living ideas: they have tensions within them, and there are places where they don’t always fit. We hope you study them, challenge them, and help us make the next version of this book even better.
> 
> Thanks for reading.
> 
> And welcome to Duolingo.
> 
> — Luis

---

### 太長了，重點摘要

#### 長遠考量

* 我們正在打造一個永恆的產品，以長期使用者留存為首要目標。
* 我們招募優秀的人才：能與 Duolingo 一同成長，並在未來數年塑造它的發展。
* 我們正在建立一個百年品牌，以充滿趣味且獨特的角色，融入學習者的生活中。

#### 樹立標竿
* 每項功能都必須直覺易用、充滿趣味、實用且精雕細琢。
* 我們確保每項重要任務都有明確的負責人。
* 我們親自體驗自家產品，發現問題並提出改進方案。
* 我們給予坦誠的回饋，對事而不對人。

#### 上線吧
* 我們最佳化「時脈」，縮短行動間的間隔，以保持動力。
* 我們每週進行數百次實驗，持續改進產品與組織。
* 我們優先投入最具影響力的專案，並果斷淘汰無效方案。
* 只有當新流程能幫助我們更快、更好的做出決定時，我們才會引入它。

#### 秀，不要光說
* 我們注重工作成果，而非過程有多艱辛。
* 我們的產品應該對於任何人都直覺易懂，不需要額外說明。
* 當我們意見不合時，我們會測試想法，讓數據來決定方向。

#### 讓一切充滿樂趣
* 我們的產品建立在遊戲化的基礎上，透過設計讓學習變得有趣。
* 我們的品牌是真摯又瘋狂的：我們擁抱讓粉絲發笑的元素，即便不是所有人都能 get 那個笑點。
* 我們的辦公環境與文化充滿趣味與包容性，讓每一位 Duo 都能感受到歡樂與連結。

. . .

**綠色機器**是我們打造一切的方式：
* 配備優秀人才
* 定義成功
* 設置護欄，長遠思考
* 建立，同時制定回饋機制
* 以迫切感與卓越執行任務
* 強化有效策略，淘汰無效方案

> ### TL;DR
> 
> #### Take the Long View
> 
> * We’re building a forever product that puts long-term user retention first.
> * We hire exceptional people who will grow with Duolingo and shape its future for years to come.
> * We’re creating a 100-year brand with delightful, quirky characters that become a part of learners’ lives.
> 
> #### Raise the Bar
> 
> * Every feature we ship must be intuitive, delightful, useful, and polished.
> * We make sure critical tasks have a clear owner.
> * We constantly dogfood our products to identify bugs and propose improvements.
> * We give candid feedback that focuses on the “what” and not the “who.”
> 
> #### Ship It
> 
> * We optimize “clock speed,” minimizing gaps between steps to maintain momentum.
> * We run hundreds of experiments each week in order to constantly improve our products and our organization.
> * We ruthlessly prioritize projects with the highest impact and quickly cut what isn’t working.
> * We’ll only introduce a new process if it helps us make faster, better decisions.
> 
> #### Show Don’t Tell
> 
> * We lead with the results of our work, not the story of its effort.
> * Our products don’t have to explain themselves—they should
> be intuitive to everyone.
> * When we disagree, we test ideas and let the metrics decide.
> 
> #### Make It Fun
> * Our product is built on play, using gamification and design to make learning fun.
> * Our brand is wholesome but unhinged: we lean into what makes our fans laugh, even if not everyone gets the joke.
> * We design our offices and culture to be quirky and welcoming, sparking joy and connection among Duos.
> 
> . . .
> 
> **The Green Machine** is our approach to building things:
> * Staff it with great people
> * Define success
> * Set guardrails and think long-term
> * Build the thing and set up feedback loops
> * Execute with urgency and excellence
> * Double down on what works, stop what doesn’t
 
---

### 閱讀前的提醒

Duolingo 是一個產品主導的組織，但這本書的想說的不僅僅是關於如何打造一個好產品，更是關於大家如何一起建立一個好公司。

並非每個章節都適用於每位員工或每個情境。請將這些原則視為一個簡單的指南，幫助你理解當我們發揮最佳狀態時是如何運作的。

> ### A Note Before Reading
> 
> Duolingo is a product-led organization. But the ideas in this book aren’t just about building a great product—they’re about building a great company, together.
> 
> Not every section applies to every employee in every situation. Think of the principles simply as a guide to understanding how we work when we’re at our best.

---

### 目錄

* 長遠考量
* 樹立標竿
* 上線吧
* 秀，不要光說
* 綠色機器
* 詞彙表


> ### Table of Contents 
> * Take the Long View
> * Raise the Bar
> * Ship It
> * Show Don’t Tell
> * Make It Fun
> * The Green Machine
> * Glossary

---
### 原則 #1 長遠考量

如果短期內有幫助，但長遠來看會傷害 Duolingo，那就是不對的。

#### Duolingo 從來不是一場短跑衝刺

Duolingo 不是一個短暫的實驗，也不是週末的副業。

我們知道，打造一個全球最好的教育 app 需要數十年的努力，這是一場耐力賽。而耐心，也就是長遠考量，並不容易。

以廣告為例。如果我們在 app 裡放入更多廣告，明天的收益就會立刻提升。但我們也清楚，過多的廣告可能惹惱使用者，扼殺長期的成長，甚至會影響我們讓優質教育普及化的目標。這是一個困難的取捨。但我們一次次選擇了長遠的視角。我們有責任如此：我們的目標很遠大，無法用其他方式來達到。

#### 創業之初

並不是每家公司都有辦法這樣運作。我們在創立初期擁有幾個優勢，使我們能夠以長遠為考量。首先，Luis 在 2009 年時，出售了他的第一家公司 reCAPTCHA。他曾說過：「這給了我彈性與遠見，能思考我們的使命，並將使命擺在第一優先。」

因此，我們立志打造一款開創性的產品——一個我們的子孫後代還會持續使用的教育工具。這個清晰的願景，加上最期投資人的信任，讓我們有餘裕去探索 Duolingo 的可能性。同樣重要的是，我們找來了一群對這個使命瘋狂的人。如果他們當時選擇進入大型科技公司，薪資可能會翻倍；但他們放棄快速致富，來到這裡，就為了打造世界上最棒的學習工具。

#### 別做蠢事

短期成功的誘惑很強大。我們在創業初期有一句簡單的座右銘：「別做蠢事。」回頭看，這其實就是「長遠考量」的最初版本。我們很清楚，如果想要真正的成功，就得避開那些看似短期內有用，但最終可能造成傷害的小手段和小聰明。

#### 押注於科技

長遠考量不僅是關於你要避免什麼，也關於你要擁抱什麼。我們是科技樂觀主義者，從一開始，我們就相信科技會進步到足以實現我們的遠大目標。押注於科技是我們運作的關鍵。例如，我們早期選擇投資語音合成技術，而不是錄製真人語音，雖然剛開始我們的音訊聽起來很機械，但我們知道這項科技會不斷進步。

#### 長遠考量的招募

招募決策是我們最重要決策之一。這也是為什麼我們願意花時間找對的人，即使這意味著等待。每位新進員工都必須符合我們的標準。這個人優秀嗎？他們願意捲起袖子親自動手嗎？他們能清楚的表達嗎？他們會將公司利益置於個人目標之上嗎？

我們不會為了填補組織裡的空缺而降低招募標準，尤其這是在尋找一起合作的成員。如同我們在 Duolingo 流傳的一句話：「寧可少個人，也不要多個爛人。」

好消息是，當你找來了對的人，他們通常會長期留在這裡。我們證實了這一點：平均來說，Duos 的在職時間比大多數科技公司的員工要長久。許多人從剛畢業的學生起步，在這裡發展他們的技能，隨著時間挑戰新的任務。無論你有多少經驗，我們都希望你能長期的在這裡。

#### 打造永恆的產品
Duolingo 的設計不僅是要讓使用者在短期內愛不釋手，更要在長期帶來深遠的影響。多年來，我們專注於打造一個實用又令人愉悅的產品，讓它成為學習者生活中不可或缺的部分。

學習——尤其是語言學習——需要長時間的規律練習。因此，我們將使用者留存率視為優先目標，並投入多年時間打磨連勝（Streak）功能。我們做得越多，讓學習者持續投入越久，他們從 Duolingo 獲得的價值就越高。

我們也不斷投資於更好的教學方式。雖然這不會立即帶來營收，但我們深知，如果產品無法兌現它的承諾，使用者最終還是會停止使用。

#### 通知機制

Duolingo 每天都會發送數百萬則訊息給學習者們，而這些通知必須在長遠考量與短期目標之間取得平衡。

增加通知次數，短期內確實能提升每日活躍使用者數（DAU），但如果使用者覺得被訊息轟炸，最終不是關閉通知，就是直接刪除 app。因此，無論短期數據顯示什麼結果，我們都會嚴格控制通知的頻率。比起眼前的成長，我們更在乎的是使用者的信任。

#### Juicy

Duolingo app 一開始不是你現在看到的這種風格。早期的介面是淺灰色背景、低飽和度的按鈕，以及一隻機械感較重的 Duo。直到2018年，幾位設計師和插畫家開始為兒童版 app 構思新風格，更鮮豔的色彩、更圓潤的邊角，還有一隻更可愛、更親切的 Duo。這樣的設計讓學習變得更像遊戲，也正是我們想要帶給大家的體驗。因此，雖然我們不認為這養的改變在短期內能帶來數據的成長，但我們還是大膽採用了這種全新的設計語言，將其使用在整個 Duolingo 生態系，這就是 Juicy。

這次改版不只是視覺上的調整，更是對未來的投資。雖然過程風險高、資源投入大，但它奠定了 Duolingo 充滿趣味性的品牌基調：生動的角色、俏皮的動畫，以及讓學習更像遊戲的體驗。從長遠來看，這套設計語言讓我們能夠隨著產品的發展不斷擴展，並保持一致的風格。

#### 設立語言能力標準

當問起某人的英文程度如何，我們希望回答會是：「我的 Duolingo 分數是70。」Duolingo 分數是對使用者正在學習的語言做的能力評估，而 Duolingo 英文測驗（DET） 則提供了一種正式認證方式，適用於大學申請等重要場合。這兩者結合，構成了我們建立語言能力標準的雙軌策略。
在 app 內顯示分數，能讓數億使用者看見它，這帶來了規模優勢。而透過 DET 認證，則讓這個分數具備公信力——甚至全球最頂尖的大學都接受它作為語言能力證明。
當然，要成為語言能力的標準衡量指標並不容易，甚至可能花費數十年——Duolingo 分數與 DET 就是我們長遠考量的最佳例證。

#### 打造未來的工程

在工程領域，長遠考量有略微不同的方式。我們知道在未來數年我們仍會不斷改進產品。因此，我們不會一開始就設計一個永久不變的系統，而是先快速測試想法，只有在成功驗證後，才投入大量工程資源。如果某項嘗試行不通，我們會果斷捨棄，保持程式碼乾淨，避免不必要的浪費。
視訊通話是一個很好的例子，我們只在它獲得使用者青睞後，才投入資源擴展與穩定系統。另一個例子是通知，當我們意識到未來幾年都會不斷測試通知文案時，便開發了一個專屬工具，讓產品經理可以自行測試文案，而不需要依賴工程團隊。
這種在速度與長期投資之間取得平衡的方式，讓我們能夠快速創新，同時確保真正有效的方案能夠長久發展，也正是我們成功的關鍵。

#### 邁向商業化

多年來，Duolingo 並沒有營利。我們將全部心力投入在擴大使用者群體，並確保學習者能持續參與。此外，我們中的一些人擔心，商業化可能會影響我們的使命。
這樣的想法在2015年 D 輪融資後開始轉變。我們開始探索不同的營收模式——應用程式內購（IAP）、廣告與付費訂閱，但有一個關鍵原則：這些做法絕不能違背我們的使命。我們不會把學習鎖在付費的高牆後面。

#### 打造變現引擎

我從應用程式內購著手，但除了連勝激凍（Streak Freeze）以外，幾乎沒什麼能買的。廣告收入也有限，我們發現每堂課結束後播放一則廣告不會影響使用者留存，但如果超過這個數量，大家就會選擇離開。
於是我們意識到，推出 Freemium 訂閱方案是擴展業務的絕佳機會。困難的是，如何讓無法負擔費用的使用者依然獲得優質的學習體驗。我們設計出訂閱方案，提供無廣告體驗，並解除愛心限制，這兩個功能減少了學習上的摩擦，讓學習流程更加順暢。多年來，我們不斷微調這個模式，但核心理念始終不變：付費產品讓我們有資源推動使命，而免費產品則是我們實現使命的關鍵。
許多投資人，甚至 Duolingo 團隊內部的一些人，曾經擔心如果免費內容做得太好，會導致使用者缺乏訂閱的動機。事實上，可及性與營收之間的拉扯可能永遠都會存在。但時間證明，我們的變現策略找到了平衡點，既建立了長期忠誠度，並發展出一個龐大的事業。

#### 打造百年品牌

透過穩健成長與巧妙行銷，Duolingo 已經成為家喻戶曉的品牌。即使從未使用過我們 app 的人，也對我們的吉祥物 Duo——一隻既可愛又偶爾有點失控的貓頭鷹——感到熟悉。我們投入大量心力塑造 Duo 的故事，以及他與其他角色所存在的世界，而這也反映了我們的遠大目標。
我們不只是要幫助人們學好法語，我們還要打造一個深入人心的品牌與角色，讓學習成為每個人日常生活的一部分，讓世界上的每個人都成為終身學習者。

#### 角色的力量

我們的角色讓學習變得有趣。這些角色由簡單的幾何形狀構成，但每個都有獨特的個性與故事。他們不僅展現了我們學習者的多樣性，也為 app 帶來了幽默與遊戲性。
這些角色的設計靈感更接近任天堂這類品牌，而非傳統的教育公司，從策略角度來看，這些角色是我們業務重要的護城河，特別是在 AI 學習工具迅速崛起的時代。與角色們建立了情感，不僅讓學習更愉快，也提升了產品的黏著度。即便有人複製了我們的 app，學習者仍然會回到 Duolingo，因為這些角色是無可取代的。

#### 下功夫行銷

在 Duolingo，我們的成長來自於打造一款人們真正喜愛，並樂於分享的產品。但除了這種自然增長，我們也善用行銷策略來進一步擴大影響力。我們的付費廣告只是為了放大口碑效應，而不是取代它，因此我們在廣告預算上相當謹慎，將資源集中在亮眼的行銷活動與即時社群操作上，以突顯品牌特色。
我們的行銷團隊擅長以低成本創造高影響力的內容。正因如此，Duo 曾在《芭比》電影首映會紅上現身、在 Peacock 串流平台上推出一檔（惡搞的）戀愛實境秀，甚至成為全球社群媒體的熱門話題。這些時刻展現了 Duolingo 俏皮又不按牌理出牌的品牌個性，也證明了口碑行銷與精準行銷的完美平衡能帶來強大影響力。

#### 學習路徑

Duolingo 原本採用樹狀結構來安排學習進度，每個主題（例如「去餐廳」）都從基礎單字開始，逐步延伸到更進階的內容。不過學習者只需要完成第一級，就能直接跳到下一個主題。雖然這種彈性讓人可以快速推進進度，但當學習者遇到更難的概念時，卻容易發現基礎知識的漏洞，導致挫折感增加。
2022年，我們做出了一個大膽的決定：以線性路徑取代樹狀結構。這種線性學習的方式讓所有學習者必須按照固定順序完成每一課，確保每個人都能打下穩固的語言基礎。這項改變牽涉到工程與設計團隊的全面調整，我們也預期學習者可能會抗拒如此劇烈的變動。事實上，短期內我們並未看到每日活躍使用者或營收等核心指標的立即提升，但我們依然認為這是正確的決定。

新架構的核心理念是優先培養真正的語言掌握能力，而非單純為了累積連續學習天數而快速通關簡單的課程，此外也讓我們更清楚掌握學習者的進度，能更精準的調整學習體驗。

有時候，長遠佈局意味著在當下做出看似不利的決策。學習路徑就是一個典型例子——它徹底改變了人們使用 Duolingo 學習的方式，也成為我們成功的重要關鍵之一。

> ### PRINCIPLE #1 TAKE THE LONG VIEW 
> If it helps in the short-term, but hurts Duolingo in the long-term, it’s not right.
> 
> #### Duolingo was never going to be a sprint.
> 
> It wasn’t a quick experiment, or a weekend side hustle.
> 
> We knew that building the best education app in the world would be a multidecade effort—and that it would require patience. But patience—that is, taking the long view—is hard.
> 
> Take advertising. We could increase revenue tomorrow by showing more ads in the app. But we know that too many ads can annoy users and stifle long-term growth, potentially compromising our goal of making the best education universally available.
> 
> This is a real trade-off. But over and over, we’ve taken the long view. We have to: our goals are too big to think any other way.
> 
> 
> #### In the Beginning
> 
> Not every company is able to operate like this. But we had a few early advantages that made taking the long view possible. For one, Luis had already sold his first company, reCAPTCHA, in 2009. As he put it: “This gave me the flexibility and perspective to think about our mission first and foremost.” So we set out to build something groundbreaking—the kind of educational tool our children and grandchildren might still be using. The clarity of this vision, along with the trust of our earliest investors, gave us leeway as we figured out what Duolingo could be. Equally important: we hired folks who were just as crazy about our mission. Back then, many of them could have doubled their salaries working at bigger tech companies. But they didn’t come here to make a quick buck—they came here to build the best learning tool on the planet.
> 
> #### Don’t Do Dumb S**t
> 
> The temptation of short-term wins can be powerful. We had a simple mantra in the early days: “Don’t do dumb s**t.” Looking back, this was the first version of “Take the Long View.” We knew that to have any shot at meaningful success, we had to steer clear of gimmicks and tricks that might seem helpful in the short-term but hurt us down the road.
> 
> #### Betting on Technology
> 
> Taking the long view isn’t just about what you avoid— it’s also what you embrace. We are tech optimists. From the beginning, we’ve believed that technology will advance enough to make our most ambitious ideas possible. And betting on that has been crucial to how we operate. For example, we invested in early text-to- speech systems instead of recording human voices: even though our audio sounded robotic at first, we knew the technology would improve with time.
> 
> #### Long View Hiring
> 
> Hiring decisions are some of the most important decisions we make. That’s why we take time to find the right person — even if it means waiting. Each new hire needs to meet our bar. Is this person exceptional? Are they willing to get their hands dirty? Are they a clear communicator? Will they prioritize what’s best for the company over their personal goals?
> We don’t compromise our hiring standards to fill a hole in the organization, especially when it comes to being a team player. As we say at Duolingo: “Better a hole than an a**hole.”
> 
> The good thing is, when you hire the right people, they tend
> to stick around. And our experience validates this: on average, Duos stay here much longer than employees at most tech companies. Many are exceptional generalists who start with us as new college grads, develop their skills here, and take on new challenges over time. Whatever your experience level, we want you here for the long run.
> 
> #### Building a Forever Product
> 
> The Duolingo app is designed to be sticky in the short- term and transformative in the long-term. For years, we’ve focused on building something so useful and delightful that it becomes an essential part of our learners’ lives.
> Learning—particularly language learning—requires regular practice over extended periods of time. That’s why we prioritize user retention, and have spent years perfecting the Streak feature. The more we can do to keep our learners committed for the long haul, the more value they’ll get from Duolingo.
> We also invest in teaching better. Even though this doesn’t generate immediate revenue, we know that if a product fails to deliver on its promise, people will eventually stop using it.
> 
> #### Notifications
> 
> Every day, Duolingo sends millions of messages to learners. These notifications present a fundamental tension between long-term thinking and short-term goals.
> More notifications leads to more Daily Active Users (DAUs)*
> in the short-term. But people who feel bombarded don’t stick around for long—they eventually turn off notifications or abandon the app entirely. That's why we put firm limits on notifications, regardless of what the short-term metrics suggest. User trust matters more than immediate gains.
> 
> #### Juicy
> 
> Duolingo didn’t always look like the app you see today. For years, it featured a light gray background, muted button colors, and a more robotic-looking Duo. But in 2018, a few of our designers and illustrators began working on a concept for a kids’ app. With brighter colors, rounder corners, and a cuter, friendlier Duo, the new design made learning feel more like a game. It was exactly the kind of playful experience we wanted for the main app. So, even though we didn’t expect it to boost metrics in the short- term, we took the leap and applied this new design language— dubbed Juicy—across all of Duolingo.
> 
> This redesign wasn’t just about aesthetics; it was an investment in the future. While risky and resource intensive, it set the foundation for the playful world that now defines our brand: expressive characters, delightful animations, and a learning experience that feels like play. By taking the long view, we created a design language that would scale with the product for years to come.
> 
> #### Setting the Proficiency Standard
> 
> When asked how much English somebody knows, we want them to say, “My Duolingo Score is 70.” The Duolingo Score is an estimate of users’ proficiency in the language they’re learning, and the Duolingo English Test (DET) is a way to certify the
> score that can be used for high-stakes purposes, like university admissions. Together, they form our two-pronged approach to becoming the standard measure for language proficiency. Putting the score in the app gives us volume—hundreds of millions of people see it. Having a way to certify it with the DET gives us credibility—the score can get you admission to even the most prestigious universities in the world.
> Of course, becoming the proficiency standard is not easy, and could take decades—but that’s exactly why the Duolingo Score and the DET are great examples of taking the long view.
> 
> #### Engineering the Future
> 
> In engineering, taking the long view requires a slightly different approach. We know that we will still be improving our products years from now. So, we don’t build systems to last forever. Instead, we test ideas quickly and only invest significant engineering resources when something is successful. If something doesn’t work, we move on quickly, keeping the codebase clean and minimizing waste.
> Video Call is a great example. We only invested in scaling and stabilizing it for long-term use once it showed traction with users. Another example relates to notifications. When we realized we’d be testing notification copy for years to come, we built a custom tool that allows Product Managers to test copy without engineering support.
> This balance—focusing on speed while reserving long-term investments for what truly works—has guided our success.
> 
> #### Becoming a Business
> 
> For years, Duolingo didn’t make money. We were laser-focused on growing our user base and keeping learners engaged. Also, some of us worried that monetizing Duolingo could get in the way of our mission.
> That perspective began to shift after our Series D funding round in 2015. We started exploring revenue models—in-app purchases (IAPs), advertising, and paid subscriptions—with one key caveat: they could never compromise our mission. We weren’t going to put learning behind a paywall.
> 
> #### Building a Monetization Engine
> 
> We started with in-app purchases, but there wasn’t much to “buy” except a Streak Freeze. Advertising was also capped. We found that we could show one ad after each lesson without affecting user retention, but more than that would drive people away.
> It became clear that introducing a freemium subscription product was the best opportunity to scale the business. The hard part was doing so while still offering an excellent product for those who couldn’t pay. We landed on a subscription package that eliminated ads and gave learners unlimited hearts. Both of these features remove friction from the app. Over the years, we’ve continued to tweak this model, but the core dynamic is the same: the paid product gives us the resources to pursue our mission at the greatest scale, and the free product is largely how that mission is achieved.
> Plenty of investors—and even some of us at Duolingo —wondered whether offering such a great free product would provide too little incentive for learners to subscribe. There will likely always be a tension between accessibility and revenue. But over time, our approach to monetization has shown that we can strike this balance, achieving long-term loyalty while building a large business.
> 
> #### A 100-Year Brand
> 
> Through steady growth and clever marketing, we’ve made Duolingo a household name. Even people who’ve never used the app are familiar with our mascot, the delightful—if sometimes unhinged—Duo. We’ve invested a ton in Duo’s journey, along with the rest of our characters and the world they inhabit. This says a lot about our ambitions. We’re not just trying to help people get better at French. We want to build a brand and set of characters that become a part of people’s lives, turning everyone in the world into daily learners.
> 
> #### Characters Count
> 
> Our characters make learning fun. Built from simple geometric shapes, each has a distinct personality and story. Together, they reflect the diversity of our learners and bring a sense of humor and play to the app.
> But these characters—inspired more by brands like Nintendo than traditional learning companies—also serve an important strategic purpose. We see this IP as a crucial moat for our business, especially in the era of AI learning tools. That same emotional connection that makes learning enjoyable also makes our product stickier over time. Even if someone cloned our entire app, learners would still come back to Duolingo for the characters.
> 
> #### Investing in Marketing
> 
> At Duolingo, we’ve grown by creating a product that people genuinely love—and love to talk about. But we’ve also figured out how to use other levers, like performance marketing, to complement that organic growth. Our paid ads exist to amplify our word-of-mouth momentum, not replace it, so we are conservative with our spend. This allows us to invest in standout campaigns and reactive social moments that set us apart.
> Our marketing team excels at creating high-impact content at a low cost. Thanks to their work, Duo has walked the red carpet at the Barbie premiere, hosted a (fake) dating reality show on the streaming service Peacock, and become an international social media star. These moments reflect the playful, irreverent energy of our brand and show how a thoughtful balance of organic growth and marketing can create meaningful impact.
> 
> #### The Path
> 
> Originally, learners navigated Duolingo through the Tree, which consisted of skills (e.g., going to a restaurant). Each skill began with basic word meanings and progressed to harder content, but learners only needed to complete the first level to move on. While this flexibility let them advance quickly, it often led to frustration when harder concepts came along and exposed gaps in their foundational knowledge.
> In 2022, we took a leap: replacing the Tree with the Path. This new linear structure requires learners to complete every lesson in sequence, ensuring a consistent and strong foundation
> for everyone. The Path was a large undertaking across both engineering and design. We anticipated that learners might resist such a dramatic change to their routine. And even though the data didn’t immediately show improvements in core metrics like DAUs or monetization, the switch was the right decision.
> It prioritized real mastery over speedrunning easy lessons to maintain streaks. It also gave us clearer insights into learner progress and greater control over the learning experience.
> Sometimes taking the long view means making bold moves that might seem counterproductive in the moment. The Path was just that. It fundamentally changed how people learn with Duolingo and has been essential to our success.

### 原則 #2 樹立標竿
要改變世界的學習方式，我們就必須做到世界級的水準。

#### 卓越不是一個崇高的理想——而是我們的基本要求。

我們期望在這裡創造出職涯中最出色的成就，不斷推動我們的技藝和創意，不僅達到我們訂下的標準，更要超越它。

然而，我們畢竟都是人，難免會犯錯。當錯誤發生時，我們不會到處追究責任，而會深入分析，找出問題所在。這就是我們不斷提升標準的方式——不在於追求完美，而是每天都進步一點。

#### 卓越文化

我們對品質的要求一開始就設立在最高點。Luis、Severin 和早期的團隊對細節的要求近乎到了苛刻的程度。（Luis 是那種至今仍會回報他在 app 中發現的每一個 bug 的難得 CEO。）卓越不是僅僅是領導層或某一位 Duo 的功勞，隨著公司成長，我們共同定訂了明確的卓越標準，並推廣到整個組織。

#### 明確的負責人
維持高標準的關鍵之一，就是明確指派負責人。也就是說，將任務分派給某個人或團隊，賦予明確的指令，告知「這項工作由你負責。」我們屢次發現，只有那些有明確負責人的事情，才能達到卓越。
隨著組織的成長，責任的歸屬會是一大挑戰。一項任務可能需要橫跨四個部門和七個團隊，但究竟誰負責哪個部分卻不太明朗。總會有一些專案很難、甚至無法界定定責任。但公司中最重要的專案，一定要有明確的負責人。

#### 對工作嚴格，對人寬容

我們的文化以溫暖和友善聞名，這點非常棒！但是這種溫暖的文化，有時會讓我們難以展開嚴肅的對話。我們在給予設計和產品回饋時一向直截了當，對於其他領域，我們也希望能更加直接。
這裡的標準是「對工作嚴格，對人寬容」，這意味著我們提供有建設性、清楚的回饋來激盪想法，而不會破壞彼此的關係。（我們關注的是「事情」本身，而非「個人」。）這同時也代表，我們願意開放心胸接受意見，不把意見視為針對個人的批評。真誠、具建設性的建議，讓我們能夠在彼此督促達到高標準的同時，也能培養出信任與協作的氛圍。

#### 親自使用

另一個維持卓越的關鍵方式，就是每天使用我們的 app。這不僅確保我們自己也愛上這個產品，同時也能迅速發現並修復漏洞。為了讓這個過程更加有效，我們開發了「搖晃以回報問題」——一個簡單的工具，只需搖晃裝置，便能讓公司內任何人立即截圖並回報問題。多年來，「搖晃以回報問題」已成為我們開發流程中不可或缺的一環，使追求 app 卓越品質變成了大家共同的責任。

#### 設立標竿
這個卓越標準究竟在哪裡？我們又該如何確保自己能達到它？讓我們來看看公司各領域的具體表現。

##### 產品與設計的標準
在產品與設計方面，有四個要素指引著我們：

* 實用性：學習者需要能從我們所打造的產品中獲得實際價值，否則我們只是在增加 app 的複雜性，反而讓學習者偏離他們原本的目標。

* 直覺性：學習者是來學習的，而不是來摸索該如何使用app。每個功能必須對所有人來說都易於操作——無論是使用 Android 的印度 75 歲長者，還是拿著 iPhone 的紐約市 16 歲青少年。如果某個功能或畫面需要額外解釋或說明，那就不合適。

* 趣味性：每項新功能都應該帶有一些樂趣與驚喜。雖然在功能的最初初版本中不必追求最精緻的動畫，但總該帶有一絲讓學習者著迷的魔力。

* 精緻度：這是讓一項功能顯得完整的關鍵。緊密的視覺設計、完美的文案與無縫的互動是基本要求，任何部分都不應該顯得突兀或不一致。例如，我們不應同時設置一個「返回」按鈕和一個功能相同的「X」按鈕。

#### 招募標準

我們的團隊成員訂下工作中所有的標準。
因此，我們堅持聘用那些傑出的人才——不僅在技能上脫穎而出，在品格上更要出眾。這可能意味著某人曾是班上的第一名，或是他們家中第一位大學畢業生，但最重要的是，他們必須是真誠且友善的人。為了維持這個標準，Luis 和 Severin 至今仍親自審核每一位新進員工。
我們絕不會為了任何人降低這個標準。例如，我們曾因一位資深主管缺乏善意而放棄聘用，儘管這個職位我們已徵才超過一年。該主管在面試中表現出色，履歷也十分亮眼，但他對接機司機表現出不尊重的態度。僅憑這一刻，我們就得知他不符合我們的要求。卓越不僅是你做了什麼，更關乎你如何對待他人。

#### 推出第一版，而非最小可行產品

在科技界，推出未完成的功能或最小可行產品（MVP）的概念相當普遍，但最小可行產品帶有一系列特定的預期與限制。
在 Duolingo，我們不做最小可行產品，我們做第一版產品。
這個差異至關重要：最小可行產品往往代表較低的品質標準，甚至可能成為推出次等產品的藉口；而第一版產品則經過精心打磨。雖然它們可能不具備所有花俏的功能，但完全符合我們的標準。有時這種作法可能需要更長的時間，但我們絕不會為了趕時間而以半成品的概念妥協使用者體驗。

> ### PRINCIPLE #2 RAISE THE BAR
> To change how the world learns, we must do world-class work.
> 
> 
> #### Excellence isn’t some lofty goal—it’s our baseline.
> 
> The expectation is that we’ll do the best work of our careers here, constantly pushing our craft and ideas to meet our bar and then exceed it.
> Still, we’re human, and we’re going to make mistakes. When that happens, we don’t chase blame. We dig in and figure out what happened. This is how we continuously raise the bar—not by being perfect, but by being a little bit better each day.
> 
> #### Culture of Excellence
> 
> Our bar for quality was set at the top and at the beginning. Luis, Severin, and the early team share a nearly ridiculous attention to detail. (Luis is the rare CEO who still reports every bug he finds in the app.) But it’s no longer just about leadership or any individual Duo. As the company has grown, we’ve worked together to define clear standards for excellence and scale them across the organization.
> 
> #### Taking Ownership
> 
> One key to maintaining high standards is assigning ownership. That means putting a person or team on a task, providing a clear mandate and saying, “You are responsible.” We’ve seen it again and again: only things that are owned become excellent.
> As we grow, unclear ownership can become a challenge. One task might stretch across four functions and seven teams, and it’s not clear who owns what. There will always be some projects where defining ownership is tricky, or impossible. But the most important projects at the company should have an owner.
> 
> #### Hard on the Work, Easy on the People
> 
> Our culture is famously warm and friendly. And that’s great! But a warm-and-fuzzy culture can make it hard to have tough conversations. We’ve always been clear when giving feedback on design and product, but we want to be more candid in other areas, too.
> The standard here is “hard on the work, easy on the people.” That means giving constructive, clear feedback that sharpens ideas without undermining relationships. (We stick to the “what,” not the “who.”) It also means being open to receiving feedback and not taking it personally. This candid, constructive approach allows us to hold each other to high standards while fostering trust and collaboration.
> 
> #### Dogfooding
> 
> Another key way we maintain excellence is by using the app daily. This ensures that we ourselves love the product and that bugs are spotted and resolved quickly. To make this process
> even more effective, we built Shake to Report, a simple tool that lets anyone in the company snapshot and report an issue instantly by shaking their device. Over the years, Shake to Report has become a vital part of our development process, making excellence in the app a shared responsibility.
> 
> #### Setting the Bar
> 
> So, where exactly is this excellence bar, and how do we make sure we’re hitting it? Let’s see what this looks like across a few areas of the company.
> 
> ##### The Bar for Product and Design
> 
> In product and design, there are four elements that guide us:
> * Useful: Learners need to get utility out of whatever we’ve built. Otherwise, we’ve made something that adds more complexity to the app and distracts learners from what they’re here to do.
> * Intuitive: Learners should be learning, not figuring out how to use the app. Every feature must be easy to use for everyone—it doesn’t matter whether they’re a 75-year- old in India using an Android or a 16-year-old in New York City on an iPhone. If a feature or screen requires explanation or additional context, it’s not right.
> * Delightful: Every new feature needs to have some amount of fun and delight. We might not need the most elaborate animations in the first iteration of a feature, but there should always be a hint of the magic that learners love.
> * Polished: This is what makes a feature feel complete. Tight visual design, perfect copy, and seamless interactions are the baseline. Nothing should feel clunky or inconsistent. For instance, we shouldn’t have both a Back button and an X button that do the same thing.
> 
> #### The Bar for Hiring
> 
> Our people set the bar for everything else we do.
> So, we insist on bringing in exceptional talent— individuals who stand out not just in their skills but in their character. That might mean someone who was at the top of their class, or the first from their family to graduate from college—but also is genuinely kind. To maintain this standard, Luis and Severin still approve every new hire.
> We don’t lower this bar for anyone. For example, we once passed on a senior executive for a role we had been trying to fill for over a year because they weren’t kind. They aced their interviews and had a strong resume but were disrespectful to the driver who picked them up from the airport. That single moment told us what we needed to know. Excellence isn’t just what you do—it’s how you treat others.
> 
> #### V1s Not MVPs
> 
> The idea of shipping unfinished features, or Minimum Viable Products (MVPs), is common across tech. But MVPs come with a specific set of expectations—and limitations.
> At Duolingo, we don’t do MVPs—we do V1s.
> The difference is important: MVPs often have a lower standard of quality and can be used as an excuse to ship subpar work. V1s, on the other hand, are polished. They may not have all the bells and whistles, but they meet our bar. Sometimes this approach takes a little longer, but we refuse to compromise our users’ experience by showing them half-baked ideas.

---

### 原則 #3 上線吧！
要讓好點子成真，我們必須迫切行動。所以，快、快、快！

#### 當 Duolingo 剛起步時，我們全都在同一間個空間裡工作。

當時我們沒有正式的產品審查會議、OKR，也沒有今天這些制度化的架構。因為沒哪個學習 app 和像我們想要做的類似，所以完全沒有可以參考的藍圖。我們只能不管成敗，邊走邊摸索。
我們真的快得不得了。高速的實驗節奏讓我們能迅速找出哪些方法有效，哪些無效，並及時捨棄行不通的部分。這原則適用於所有領域：產品、招募、工程，乃至整個業務。我們以超高速不斷測試與學習。

即便到了今天，情況依舊如此。
我們每週都會發佈新版的 iOS 和 Android app，而公司內隨時都有數百個實驗在進行。沒有這個原則，Duolingo 絕不可能有今天的成就。「上線吧！」讓我們領先於競爭對手；「上線吧！」讓 Duolingo 成為一個有趣的工作環境；「上線吧！」確保我們的產品不會停滯。

#### 快、快、快！

Duolingo 是由數以千計的實驗*累積而成。我們進行實驗的速度（無論成敗）越快，app 的改進和我們使命的推進也就越迅速。隨著時間的推移，每一次改變都在累積，形成一個滾雪球式的成長循環。
快速上線還能避免我們陷入冗長的辯論和無謂的猜測，因為在真實世界中測試所得到的資訊，比任何內部討論都來得真實可靠。所以，我們必須迅速行動，啟動這些回饋循環，讓真實數據指引我們前進。

> �*實驗：實驗就是測試什麼方法有效、什麼方法無效。A/B 測試讓我們可以同時比較兩個或更多選項的表現。
> 
> �PR：Product Review 這是我們對 app 每項改動進行綠燈批准的會議。由產品團隊主導，但任何人都可以旁聽！

##### 時脈
「時脈」是一種驅動我們工作方式的心態。這個概念來自微處理器技術，時脈用來衡量系統處理指令的速度。我們借用這個術語來描述縮短行動之間間隔的重要性：從決策做出到執行，或從給出回饋到實施改變，時間間隔越短越好。

提升時脈有助於減少閒置時間，確保最重要的專案能夠真正落實。我們不需要等上整整一個月，才能看到專案的下一個版本。縮短這些間隔，意味著我們能更快上線，從而更迅速地學習與改進。這並非在催促，而是不允許任何中斷拖慢我們的腳步。

#### 無情的優先排序
儘管我們渴望快速行動、提高時脈，但必須確保我們始終在做正確的事。對 Duolingo 來說，優先排序有時被形容為「無情」：我們會根據對學習者影響最大的項目，果斷決定公司的聚焦重點。
決定優先順序始於明確的目標。對每一項計畫，我們都會問：這如何推動我們的使命？它會帶來哪些可衡量的成果？如果某件事無法在實質上推動進步，不論已經投入多少努力，都將被砍掉。一次高影響力的成功，遠勝於多個零星的小成就。
這種心態同樣延伸到我們的產品上。我們會刪除那些無法帶來價值的功能，移除不必要的複雜性，並始終保持對使命的高度聚焦。放棄無效的部分，往往能產生與創造新功能相同的效果。

> ⚠組織結構上線
> 隨著團隊規模擴大、專業分工日益明細，存在一個風險：我們的產品可能會反映出公司的組織結構，而非提供學習者所需的無縫體驗。這種現象被稱為「組織結構上線」（Shipping the Org）。舉例來說，app 中的各個分頁——如排行榜和個人檔案——分別由不同團隊管理，各自有著獨立的目標。隨著時間推移，就行成了設計上的不一致。為了避免這種情況，我們必須始終從整體角度考量 app 的使用體驗。

#### 實驗文化

「上線吧！」不僅僅關乎速度，更在於創造盡可能多的機會來學習與進步。我們喜歡嘗試、敢於冒險——有時甚至會失敗。但每一次實驗都讓我們更接近發現有效的方法。

##### 99 個爛點子

我們一些最出色的功能和行銷活動，往往來自於那些看似荒謬、不可能的問題。我們在領導團隊的離線會議中，有一個傳統稱作「99 個爛點子」，在會議中我們會腦力激盪一些離譜的概念——像是 Duo 最新的惡作劇，或是將我們的股票代碼改成 LILY。
這種精神不僅存在於高層，而是貫穿整個組織，讓大家都有空間挑戰傳統觀念，提出大膽的問題。假如你能和 Duolingo 的角色對話會怎樣？如果 Duo 在超級盃上只有五秒鐘，他會做什麼？假如語言認證考試可以在家進行，會有何改變？多年來，這些問題持續幫助我們發掘新機會，既讓學習者感到驚喜，也推進了我們的使命。


#### 適度的流程

隨著 Duolingo 的不斷成長，保持敏捷變得越來越具挑戰性。我們需要一些防護措施與流程來避免事情失控，但同時也希望避免不必要的官僚作風。問題在於：如何在不拖慢速度的前提下，引入合適的流程？好的流程應該能夠減輕工作負擔、提升品質，並促成更好的決策。舉例來說，就是產品審查（PR）。在早期，Luis 常在非正式會議中做出產品決策，結果導致了混亂：並非所有相關人士都能參與或獲知，更糟的是，有時候也不清楚這些決策是否具有約束力，或僅僅是 Luis 的隨口之言。我們需要一個更好的方式。受到工程領域程式碼審查流程的啟發，我們引入了正式的產品審查架構。如今，PR 會議確保所有人都清楚決策，並讓所有相關人士及時獲知。會議還會邀請來自產品與設計部門的輪值領導參與，以確保多元觀點。PR 的成功為其他團隊樹立了典範。例如，行銷團隊也採用了「行銷審查會」，為他們的活動帶來同樣的清晰度與一致性。這些流程幫助我們維持品質標準，同時使公司內部能更迅速、明確的做出決策。
 
> ⚠在取捨之間取得平衡
> 「樹立標竿」與「上線吧！」之間存在著一種拉扯。當二者發生衝突時，我們的使命便是最佳的指引。關鍵在於：這項決策如何能改善教育，使其更易於普及？往往這意味著要放棄完美主義。例如，生成式 AI 讓我們能以前所未有的速度和規模創造內容。儘管早期版本不夠完美，但它們現已為數百萬使用者帶來價值，而品質也會隨著時間逐步提升。

> ### PRINCIPLE #3 SHIT IT!
> 
> For a good idea to become reality, we need to move with a sense of urgency. So Go, Go, Go!
> 
> #### When Duolingo was starting out, we were all sitting in one room.
> 
> We didn’t have formal Product Reviews, or OKRs, or any of the structure we have today. There was no blueprint because no other learning app was doing what we were trying to do. We were—for better or worse—making things up as we went along.
> We were also fast as hell. And the pace of our experimentation allowed us to quickly figure out what was working, and ditch what wasn’t. This applied across everything: product, hiring, engineering, and our business as a whole. We were testing and learning at warp speed.
> 
> It’s still like this even today. We ship new versions of our iOS and Android apps every week. And we’re running hundreds of experiments* across the company at any given time. Duolingo goes nowhere without this principle. “Ship It” keeps us ahead of our competitors; “Ship It” makes Duolingo a fun place to work; “Ship It” ensures that our product never sits still.
> 
> #### Go, Go, Go!
> 
> Duolingo is the sum of thousands of experiments. The faster we can run experiments—successful or not—the faster we can improve the app and advance our mission. Over time, each of these changes builds on one another, creating a cycle of compounding growth.
> Shipping fast also lets us avoid lengthy debates and guesswork about what we should be doing. That’s because testing in the real world gives us better information than any internal discussion ever could. So, we move quickly—to start these feedback loops and let real data guide our work.
> 
> > �*Experiments: Experiments are tests to see what works and what doesn’t. A/B tests are a specific type of experiment where we simultaneously run two or more options against one another.
> > 
> > �PR: Product Review. The meeting where we green-light every change to the app. Led by the Product Org, but anyone can listen in!
> 
> ##### Clock Speed
> 
> “Clock speed” is a mindset that drives how we work. The concept comes from microprocessor technology, where clock speed measures how quickly a system can process instructions. We use the term to talk about minimizing the gaps between actions: the time between when a decision is made and when it’s implemented, or when feedback is given and changes are made.
> 
> Increasing clock speed helps us reduce idle time and make sure that the most important projects actually get done. We should almost never have to wait a month to see the next iteration of a project. The more we can close these gaps, the faster we ship it, and the faster we can learn and improve. It’s not about rushing—it’s about never letting a break in the chain slow us down.
> 
> #### Ruthless Prioritization
> 
> As much as we want to move fast and increase clock speed, we always need to make sure we’re working on the right thing. At Duolingo, prioritization is sometimes described as “ruthless:” we are decisive about what we focus on as a company, based on what will have the largest impact on our learners.
> Deciding what to prioritize starts with clearly defined goals. For every initiative, we ask: How does this contribute to our mission? What measurable outcomes will it drive? And if something doesn’t move the needle in a meaningful way, it’s cut—no matter how much effort has already gone into it. One high-impact win always outweighs a handful of small scattered efforts.
> 
> This mindset extends to our product. We cut features that don’t deliver value, remove unnecessary complexity, and stay laser- focused on our mission. Letting go of what’s not effective is often as powerful as creating something new.
> 
> > ⚠ Shipping the Org
> > 
> > As teams grow and become more specialized, there’s a risk that our product will mirror the organization’s structure rather than delivering a seamless experience for learners. This is called “shipping the org.” For example, the tabs across the app—like Leaderboards and Profile—are managed by different teams, each with distinct goals. Over time, this has led to inconsistencies in their design. To counter this, we always need to consider the holistic experience across the app.
> 
> #### Culture of Experimentation
> 
> “Ship It” isn’t just about speed; it’s about creating
> as many opportunities as possible to learn and improve. We like to play around, run a little wild—and sometimes fail. But each experiment brings us closer to seeing what works.
> 
> ##### 99 Bad Ideas
> 
> Some of our best features and campaigns have come from asking ridiculous, unlikely questions. We practice this at leadership offsites during a tradition we call “99 Bad Ideas,” where we brainstorm outrageous concepts—like Duo’s latest hijinks, or changing our stock ticker to LILY.
> 
> But this spirit extends across the organization,where we make space for challenging assumptions and asking bold questions. What if you could talk with Duolingo characters? What would Duo do with five seconds at the Super Bowl? What if language certification tests could be taken at home? Over
> the years, these types of questions have helped us consistently uncover new opportunities to delight our learners and advance our mission.
> 
> #### The Right Amount of Process
> 
> As Duolingo grows, staying agile becomes more challenging. We need guardrails and processes to keep things from spiraling out of control, but we also want to avoid unnecessary red tape. The question is: How can we add the right processes without slowing ourselves down?
> Good processes should reduce workloads, improve quality, and lead to better decisions. One example of this is Product Review (PR). In the early days, Luis often made product decisions
> during informal meetings, which sometimes got messy. Not all stakeholders were included or informed; even worse, it wasn’t always clear if decisions were binding or if Luis was just musing. We needed a better approach.
> Taking inspiration from engineering’s code review process, we introduced a formal structure for Product Review. Today, PR ensures that everyone is clear on what decisions were made, and that all relevant stakeholders are informed. The meeting also includes a rotating group of leaders from Product and Design who weigh in, ensuring diverse perspectives.
> The success of PR has set a precedent for other teams. Marketing, for instance, has adopted a Marketing Review, which brings the same clarity and alignment to their campaigns. These processes help us maintain our quality bar—and make faster and visible decisions across the company.
> 
> > ⚠ Navigating Trade-offs
> > 
> > There’s a natural tension between “Raise the Bar” and “Ship It.” When they clash, our mission is a great guide. The question is: How will this decision improve education and make it more accessible? Often, it means letting go of perfection. Generative AI, for example, lets us create content at a speed and scale we never thought possible. Early versions aren’t perfect, but they deliver value to millions now—and the quality will improve over time.
> 
---

### 原則 #4 秀，不要光說
我們採用清晰、簡潔，以數據和實際影響為基礎的溝通方式。

「秀，不要光說」意味著我們以工作的成果為主，而非僅僅講述付出的努力。
這種方法與大多數人在學校或過去的工作中所學的截然不同。在那些場合，我們常被教導如何以具有說服力的簡報和故事來推銷自己。儘管這些技巧有其價值，但它們並非揭示真相、解決問題或創造偉大事物的方法。

#### 數字就是故事

當有數據指標可用時，指標應該成為我們工作與溝通的核心。決策必須建立在證據之上，而非抽象的敘述。
透過專注於實際成果——例如一項新功能對每日營收的影響——我們能迅速評估某項內容是否適合納入 app。不過，這種精神不僅限於 app 本身。舉例來說，我們也會衡量辦公空間的使用狀況（以及未被使用的部分），以便讓每一個新空間都比之前更好。

#### TL;DR

我們「秀，不要光說」的一個關鍵方式是透過 TL;DR（重點摘要）——在任何重要溝通的最上方提供執行摘要。無論是功能效能分析、會議預讀，還是新政策公告，我們都會使用這種方式。
撰寫精鍊的 TL;DR 能大幅提高你的工作被看見和記住的機率。它們使得複雜資訊更易於理解，更重要的是，能促使我們的思考更清晰。要寫出好的 TL;DR，你必須將訊息濃縮到最核心的要點。

> ⚠ 數據的暴政
> 
> 過分專注於數字有時會讓我們偏離正軌。指標固然寶貴，但若單獨看數據，往往只能呈現片面情況。例如，學習成果——即學生在完成一課後應該掌握的知識——就是極難精準量化的項目。在這種情況下，我們必須依靠直覺和專業判斷。

#### 少說點
##### 做出原型，而非簡報

僅僅談論點子，遠不如付諸實作來得有效。原型能讓我們將概念具體化、達成共識，並迅速推動計畫前進。這在處理如將 AI 整合進現有的功能等，這類複雜的挑戰時，顯得尤其重要。

#### 優秀的產品不用解釋

我們的 app 以直覺易用為主。相較以彈出訊息或冗長的新手指引來告訴學習者如何使用 Duolingo，我們以設計、動畫和簡單的提示來完成引導的工作。無論你是第一次，還是第一百次打開 Duolingo，都應該無需額外指引，即可專心學習。

事實上，研究顯示最有效的學習是通過實際體驗，而非長篇大論的說明。舉例來說，我們不單單解釋文法規則，更透過互動練習和吸引人的視覺呈現來展示語言的規則。

#### 以點子優先，捨棄自我

優秀的點子不需要推銷簡報，而需要機會證明自己。在 Duolingo，我們重視成果勝於意見。透過賦予團隊探索大膽概念的權限，並以數據指引方向，我們確保最好的點子最終能夠脫穎而出。

> ⚠ 表揚創新者
> 
> 我們一向以團隊為先，但也有些時刻必須表彰那些超越常規、卓越表現的個人。每年的 Duoversary（Duolingo 週年慶）中，我們都會選出幾位傑出貢獻者，頒發 Duolingo 創新獎。

#### 異議也要全力前進

意見分歧在所難免，但我們選擇以行動化解僵局。當雙方意見相左時，我們會承諾按照某個決策前進，讓結果來證明一切。例如，即使像 Luis 這樣的高層對某個點子抱有疑慮，他也常會說：「就試試看吧——我們看看結果如何。」（這正是排行榜功能誕生的過程，如今它是 app 中的關鍵功能之一。）
這種思維模式不僅適用於產品開發。例如，在我們的社群媒體團隊中，即便是初階成員也被信任，能夠提出大膽點子並衡量其影響。透過創造實驗的空間，我們確保最終是成果而非僅僅是意見在引領方向。

#### 信任電池

建立信任是這個策略的關鍵的一環。
在 Duolingo，信任不是理所當然的，而是需要爭取的。通過具有影響力的工作，每個人都在為自己的「信任電池」充電。無論你是實習生還是新上任的主管，從展示具有意義的貢獻開始，每一次的付出都在為這個電池充電，隨著時間逐漸增加在團隊合作、決策和承擔責任的信任。


> ### PRINCIPLE #4 SHOW DON'T TELL
> We use clear, concise communication that is grounded in data and real impact.
> 
> #### “Show Don’t Tell” means we lead with the results of our work, not the story of its effort.
> 
> This approach is different from how most of us were taught. In school or past jobs, we often learned to communicate to persuade—selling ourselves with pitches and stories. While those skills have their place, they’re not how we uncover the truth, solve problems, or build great things.
> 
> 
> #### Numbers Are the Story
> 
> Metrics, when available, should be at the center of all our work and communications. Decisions must be grounded in evidence, not abstract narratives.
> By focusing on actual results—like the effect of a new feature on daily bookings—we can quickly assess whether something belongs in the app. But this spirit extends well beyond the app. For example, we measure how our offices are being used (and not used), so we can make each new space better than the last.
> 
> #### TL;DR
> One key way we Show Don’t Tell is through TL;DRs—executive summaries at the top of any important communication. We use them in many places, from feature performance analyses and meeting prereads to new policy announcements.
> Crafting strong TL;DRs boosts the chances that your work will be seen and remembered. They make complex information more digestible and, importantly, encourage clearer thinking. To write a TL;DR, you have to distill your message down to its most essential points.
> 
> > ⚠ The Tyranny of Metrics
> > Fixating on the numbers can sometimes lead us astray. Metrics are valuable, but in isolation, they paint an incomplete picture. For example, learning outcomes—that is, what a student should know after completing a lesson—are notoriously tricky to measure. In cases like these, we have to trust our intuition and expertise.
> 
> #### Say Less
> 
> ##### Prototypes, Not Pitch Decks
> 
> Talking about ideas is rarely as effective as building them. Prototypes allow us to bring concepts to life, align on a shared vision, and move forward quickly. They’re especially important when dealing with complex challenges like integrating AI into an existing feature.
> 
> #### Great Products Don’t Have to Explain Themselves
> 
> Our app is designed to be intuitive. Instead of telling learners how to use Duolingo with pop-over messages and lengthy onboarding flows, we let design, animation, and simple prompts do the “showing.” When you open up Duolingo for the first (or hundredth) time, the learning experience should require no instructions. That way, you can actually focus on learning.
> And the actual learning is shaped by this principle, too. Research shows that the most effective learning comes through experience, not a long list of instructions. Rather than explaining grammar rules, for example, we demonstrate language patterns through interactive exercises and engaging visuals.
> 
> #### Ideas Before Egos
> 
> Great ideas don’t need a sales pitch—they need a chance
> to prove themselves. At Duolingo, we prioritize results over opinions. By empowering teams to explore bold concepts and letting metrics guide the way, we ensure that the best ideas rise to the top.
> 
> #### Disagree and Commit
> 
> Disagreements are inevitable, but here, we handle them by taking action instead of getting stuck. When two parties disagree, both commit to moving forward with a decision and letting the results speak for themselves. For example, even when someone like Luis has doubts about an idea, they’ll often say, “Go ahead and test it—let’s see what happens.” (This is exactly what occurred with Leaderboards—now a key feature on the app.)
> This mindset extends beyond product. On our social media team, for example, junior team members are trusted to run with bold ideas and measure their impact. By creating space for experimentation, we ensure that outcomes—not opinions—lead the way.
> 
> 
> > ⚠ Celebrating Innovators
> > 
> > We tend to be team first. But there are select moments when individual work that goes above and beyond must be celebrated. Each year at Duoversary, we pick out a few standout contributors and give them the Duolingo Innovation Award.
> 
> 
> #### The Trust Battery
> 
> Building trust is an essential part of this approach.
> At Duolingo, trust isn’t assumed—it’s earned. Through impactful work, everyone powers their Trust Battery. Whether you’re an intern or a new executive, you
> start by demonstrating your value with meaningful contributions. Each contribution charges the battery, creating a reserve of trust that strengthens collaboration, decision-making, and accountability over time.

---

### 原則 #5 讓一切充滿樂趣！
我們為所做的一切注入幽默感、樂趣與創意。

#### 學習不必無聊，工作也一樣。

當你進入 Duolingo 的世界時，會立刻感受到濃厚的幽默氛圍。這裡不是一本正經、刻板正式的環境，而是一個充滿奇思妙想的世界——比如，一隻巨大的毛絨貓頭鷹主演假百老匯音樂劇（還是在冰上表演！），又或者我們會大膽提出各種瘋狂的點子，例如在愚人節推出「語言學習衛生紙」的行銷活動。在這裡，沒有人能逃過玩笑——就連 CEO 也不例外。

#### 以遊戲為基礎的產品

學習語言的方法有很多種，但如果學習者無法投入，那些方法就行不通。
從一開始，我們就決定將遊戲化元素融入 app。隨著時間的推移，我們不斷引入更多互動機制，讓學習者願意持續回來進步。然而，這些策略並非我們與眾不同的唯一原因。
Duolingo 和傳統教育工具完全不同。在這裡，你永遠無法預測接下來會發生什麼。課程可能會像脫口秀或電玩遊戲一樣呈現，學習的句子可能會讓人哭笑不得，比如「你的熊正在喝啤酒」，而角色 Lily 甚至會用諷刺的慢速鼓掌來「鼓勵」你的進步。這些幽默時刻——角色、動畫、荒誕的驚喜——不只是為了娛樂，更是吸引學習者保持動力的重要元素。

#### 你可以有不止一種身份

Duolingo 很難被分類，我們不是純粹的遊戲，也不僅僅是教育產品。正是在那模糊的邊界上，隱藏著魔法。事實上，我們正與 TikTok、Instagram 以及線上遊戲等平台爭奪使用者的注意力，因此必須讓學習變得同樣有趣。這些平台都被設計來讓人永無止境的滑動與觀看，而使 Duolingo 與眾不同的是，我們的使用者帶著一個明確目標而來：學習。這不是無腦的娛樂，而是一種富有成效與目標性的時間運用。而那些有趣、意外的瞬間與獨特設計，正是讓你持續留下來的原因。

#### 怪誕文化
##### 打開大門

在某些公司，走到走廊盡頭會有一間擺滿巨型紅木桌的會議室，所有真正的決策都在那裡做出；但在這裡並非如此。（事實上，Luis 常用的會議室就像一個公開的魚缸。）我們對公司中最重要的議題都保持高度透明——即使是其他公司可能選擇隱藏的部分。與 Luis 的問答環節便是一個明顯例證。不僅如此，在 Duolingo，我們始終保持開放：即使是最高層的主管，也只是一則私訊的距離。公司內的任何人都可以參加產品審查會。這樣的開放與透明，為我們敢於冒險、接受怪誕的挑戰提供了基礎。

> ⚠ 尊重界線
> 
> 我們之所以能夠搞怪與大膽嘗試而不受批評，是因為公司內始終有著關懷與尊重的基準線。由於團隊成員的背景、經歷與觀點很多元，我們必須謹慎體察——一個人覺得好笑的事，可能不見得適合另一個人。這裡的每個人都是成年人，我們期望你能夠尊重彼此的界線。

##### 設計中的喜悅

我們的產品之所以有趣，仰賴打造它的每一個人。只要走進辦公室，就能感受到這份活力：你可能會看到一個真人大小的 Duo 在大廳做體操，或是不經意間撞見超過 100 個從填字遊戲到生蠔俱樂部應有盡有的社團；或是在十月時，遇上年度匹茲堡小狗遊行。這一切絕非偶然。優秀的企業文化難以打造，卻也極易流失，而這正是我們成功的關鍵之一。
這種精神在我們的年度冬季「Getaway」活動中達到巔峰，屆時整間公司都會前往坎昆，沒有會議、沒有講座，也沒有訓練課程。我們的目標很簡單，就是提供一個無壓力的空間，讓 Duolingo 同仁能彼此交流、放鬆身心。我們相信，當大家真心享受工作環境與彼此的陪伴時，工作自然會變得更好。

#### 溫情又瘋狂

多年來，我們嘗試了各種不同的形式、語氣與設計語言，最終確立了我們獨有的品牌風格：既充滿溫情，又帶點瘋狂。

##### 堅持風格

找到我們的風格花了一段時間，尤其是在對外行銷上。起初，我們試圖吸引最廣泛的受眾，但結果卻缺乏獨特性；在行銷上，平淡無奇是最致命的。於是，我們轉換策略，使得行銷方式變得怪異、出人意料且常帶幽默感。
幽默並非總能精準量化——它主觀、甚至可能引起兩極反應。為了完全釋放 Duo 幽默的魅力，我們必須接受並非所有人都能 get 到笑點。真正重要的是，那些 get 到笑點的人會深深喜愛，而我們也會竭盡全力去培養這份熱情。

##### Duo 的雙重性

我們的吉祥物最初是為了鼓勵大家日常學習而設計，但當網路接觸到他之後，逐漸演變出更複雜、甚至帶點恐嚇意味的個性，並擁有了自己的傳說。他依然可愛討喜，但也能不擇手段的暫時搬遷你的家人，只為確保你能完成課程。
正因為我們擁抱這份幽默，Duo 迅速成為網路爆紅的明星，從《週六夜現場》、熱門電子遊戲、名人的 Instagram 上，到處都能看到他的蹤影。從 Buff Duo 到 Anime Duo，各式各樣瘋狂的迷因層出不窮。

##### 愚人節
愚人節對 Duolingo 來說再適合不過了：任何事物都可以成為玩笑的素材，越瘋越好。我們在公司初期便發現，愚人節的惡作劇是製造話題、展現獨特幽默感的絕佳方式。從最初的 Duolingo 枕頭，到後來大規模的活動——例如 2024年的 Duolingo on Ice，就曾在社群媒體上創下1億次的曝光量。

#### 與 Duo 的五秒鐘

超級盃 LVIII，全世界約有兩億觀眾正在密切鎖定。突然間，一隻亮綠色的貓頭鷹從他的屁股中射出另一隻貓頭鷹，提醒你「記得做 Duolingo」。
這不是典型的超級盃廣告，但無疑是 Duolingo 的作風。這短短的五秒鐘（於2024年2月11日播出），是跨越6個團隊，經歷數個月合作的結晶。我們不想支付傳統 30 秒廣告的高昂費用，於是自我挑戰：如何在僅僅五秒內造成轟動？我們知道每個像素都至關重要。沒有浮誇或冗餘的時間，因此我們完全擁抱 Duo 那怪誕、不受拘束、出乎意料的特質。當關於該呈現「多少屁股」的討論爆發時，我們知道，這個點子必定是贏家。最終，這場賭注獲得回報。以極低成本，我們的廣告創造了與當年其他超級盃廣告相媲美的話題效應，並多次入選各大「最佳廣告」名單。它有趣、出乎意料且不把自己看得太嚴肅——這正是推動我們品牌成功的秘訣。


> ### PRINCIPLE #5 MAKE IT FUN! 
> 
> We bring a sense of humor, joy, and imagination to everything we do.
> 
> #### Learning doesn’t have to be boring, and neither does work.
> 
> There’s a palpable sense of humor when you enter the world of Duolingo. This isn’t a culture of poker faces and formalities. It’s a world where gigantic, plush owls star in fake Broadway musicals—on ice. Where any wild idea is on the table, like an April Fools campaign to sell language-learning toilet paper. Where no one is safe from the joke (not even the CEO).
> 
> #### A Product Built on Play
> 
> There are lots of ways to teach a language. But none of them work if learners aren’t engaged.
> From the beginning, we made the decision to gamify the app. Over time, we’ve expanded this by introducing more and more engagement mechanics that keep learners coming back to further their progress. But these tactics aren’t the only thing that sets us apart.
> Duolingo feels like an entirely different universe from traditional education tools. Strange, unexpected things happen here. Lessons are formatted like talk shows and video games; sentences like “Your bear is drinking beer” verge on the absurd, and the character Lily sarcastically supports your progress with a slow clap. These moments of delight—characters, animations, absurd surprises—do more than entertain; they play a key role in keeping learners engaged.
> 
> 
> 
> #### You Can Be More Than One Thing
> 
> Duolingo doesn’t fit neatly into one category. We’re not a game, but we’re not just an education product either. Along that blurry line lies the magic. The fact is, we’re competing with platforms like TikTok, Instagram, and online games for attention, so we have to make learning as fun as any of them. These platforms are designed to keep people endlessly scrolling and watching. What sets Duolingo apart is that our users come with a clear goal: learning. It’s not mindless entertainment; it’s a productive and purposeful use of your time. And the fun, the unexpected moments, and the quirky design are what make you stay.
> 
> 
> 
> #### Quirky Culture
> ##### Open Doors
> 
> At some companies, there is a room at the end of the hall with a giant mahogany table where all the real decisions are made. It’s not like that here. (In fact, Luis’s go-to conference room is a public fishbowl.) We’re open about the most important issues at the company—even ones that other places might try to keep quiet. Q&A with Luis is one space where this transparency is obvious. But more generally across Duolingo, we make a point of being available: even our most senior leaders are one DM away. Anyone at the company can attend Product Review. This openness and transparency set the conditions for taking risks and getting weird.
> 
> 
> 
> #### Joy by Design
> 
> Our product is fun because of the people who build it. It’s obvious to anyone who walks into the office:
> on any given day, you might see a human-size Duo practicing calisthenics in the atrium, or stumble upon one of more than 100 clubs devoted to everything from crossword puzzles to oysters. Maybe you’re around in October and catch the annual Pittsburgh Puppy Parade. None of this is by accident. A great culture is hard to build, easy to lose, and essential for our success.
> 
> This reaches a peak during our annual winter Getaway, when the entire company decamps to Cancun without agendas or panels or training sessions. The goal is simple: give Duos a low-pressure space to connect and unwind. We believe that when we genuinely enjoy our working environment and each other’s company, work becomes better, in all senses of the word.
> 
> 
> 
> > ⚠Respect Boundaries
> > 
> > The reason we can be goofy and experiment without judgment is because we have a baseline of care and respect within the company. With a diverse team of backgrounds, experiences, and perspectives, it’s important to be thoughtful—what’s funny to one person might not land for another. Everyone here is an adult, and we expect you to respect people’s boundaries.
> > 
> 
> 
> #### Wholesome and Unhinged
> 
> Over the years, we've experimented with different formats, tones, and design languages—eventually landing on our unique brand: wholesome and unhinged.
> 
> 
> #### Committing to the Bit
> 
> It took some time to find our voice, especially with our external marketing. Early on, we tried to appeal to the broadest possible audience, but we ended up with nothing distinctive to say. And in marketing, there’s nothing worse than being bland. So we changed tack, and our approach to marketing became weird, unexpected, and often funny.
> Humor doesn’t scale perfectly. It’s subjective, sometimes polarizing. So to unleash the full power of Duo humor, we had to accept that not everyone would get the joke. What truly matters is that people who do get it love it—and we do everything we can to nurture that passion.
> 
> 
> #### Duality of Duo
> 
> Our mascot was initially designed to encourage regular practice. But once the internet got their hands on him, he grew into a more complicated—even menacing—character with his own lore. He’s still cute and cuddly. But he’s also willing to temporarily relocate your family to ensure you finish your lessons.
> By leaning into the joke, Duo has become a bona fide viral sensation. He’s shown up everywhere from Saturday Night Live to popular video games and celebrity Instagrams. There are galaxies of crazy memes, from Buff Duo to Anime Duo and more.
> 
> 
> 
> #### April Fools
> 
> April Fools is the perfect holiday for Duolingo: everything is
> fair game for a joke, and the further you push it, the better. We realized in the early years of the company that April Fools stunts were a great way to generate buzz and celebrate our quirky sense of humor. Our earliest experiments, like the Duolingo Pillow, have evolved into full-scale campaigns—like 2024’s Duolingo on Ice, which garnered 100 million social media impressions.
> 
> 
> #### Five Seconds with Duo
> 
> Super Bowl LVIII. 200 million viewers are watching around the world. All of a sudden, a bright green owl shoots another owl out of his butt, reminding you to "Do your Duolingo."
> It wasn’t your typical Super Bowl ad—but it couldn’t have been more Duolingo.
> Those five seconds, which aired on February 11, 2024, were the culmination of months of collaboration across a half dozen teams. We didn’t want to pay for a 30-second spot, so we gave ourselves a challenge: How could we make a splash in just five? We knew that every pixel mattered. There wasn’t time for flash or filler, so we embraced the quirky, unhinged, unexpected nature of Duo himself. When debates broke out over the “right amount of butt” to show, we knew we had a winning idea.
> The gamble paid off. For a fraction of the cost, our ad generated as much buzz as any other Super Bowl ad that year, and appeared on multiple “best of” lists. It was playful, unexpected, and didn’t take itself too seriously—exactly the formula that has driven our success as a brand.

---
### 綠色機器

我們的原則提供了理論基礎，而「綠色機器」則將這些理論付諸實踐。

#### 我們的流程

目前為止，我們已經探討了許多我們的原則——它們的歷史、存在的原因，以及它們的意義。「綠色機器」是一個將這些原則轉化為實際行動的框架。

這種方法最初在我們創業初期自然形成，並在之後的每一年裡持續精煉。（在這個過程中，它促成了一些我們最重要的創新與最大的成功。）你可以把綠色機器視為持續小幅度改變的一個過程。當某個小改變能夠提升數據指標時，我們就會進行更多類似的改變。

最基本的綠色機器運作方式如下：聚集優秀的人才，給他們自由實驗的空間，然後投入有效的方案。

如果你在某個問題上遇到瓶頸，可以對照以下六個步驟檢視問題所在。也許進展不順利，是因為你沒有充分考慮團隊組成，或者缺乏適當的回饋機制。綠色機器模型能幫助幾乎任何專案回到正軌。

#### 綠色機器：六個步驟

1. 配備優秀人才
出色的實驗需要一支能夠迅速腦力激盪、執行並靈活轉變策略的卓越團隊。這正是我們在招募時設下高標準，並大量投資於人才的原因。我們喜歡從精簡而充滿活力的團隊開始，只有在證明成功後，才逐步擴編。

2. 定義成功
我們始終設立明確且可量化的目標——無論是每日活躍使用者、訂單收入或社群曝光量。但對於早期專案來說，數據指標可能尚未成熟。在這種情況下，我們會定義出最佳的質化目標，逐步修正至清晰，並持續留意任何有用的訊號。

3. 設置護欄，長遠思考
我們透過設置護欄（Guardrails），來確保我們的工作能在長期造福 Duolingo 和學習者，這與我們的核心原則「長遠考量」完全一致。精心設計的護欄能幫助我們聚焦於可持續且有意義的成長，確保每項實驗都符合更高層次的目標。

4. 建立產品，制定回饋機制
創造卓越產品的最快方法不是無止境的討論，而是動手做。我們直接開始構建，並建立有效的持續回饋機制。這些回饋來源包含：量化數據（如 A/B 測試結果、社群曝光度、學習成效研究）和質化回饋（如內部測試）。在專案初期，質化回饋通常比量化數據更為重要，隨著專案發展，才逐步轉向數據驅動決策。

5. 以迫切與卓越執行任務
因為小幅改進具有累積效應，所以拖延的代價相當高。但如果行動過快，也可能導致馬虎的產出。在這一步驟，我們持續（且迫切）的推出符合我們標準的成果。

6. 強化有效策略，淘汰無效方案
當某個方案行得通時，我們會投入更多資源，持續發展它（甚至投入數年）；而對於那些無法達到成效的專案甚至整個產品，我們也必須敢於結束它。

> ⚠ 計劃的一部分
> 重要的是，綠色機器並不是計劃的替代品。我們仍然擁有季度 OKR、年度目標及長期財務計劃，不同的是，我們不會依賴多年的產品開發路線圖。

> ### THE GREEN MACHINE
> 
> Our principles provide the theory. The Green Machine puts that theory into practice.
> 
> 
> ### Our Process
> 
> By this point, we’ve covered a lot about our principles—their history, why we have them, and what they mean. The Green Machine is a framework for putting them to work.
> This approach emerged organically during our earliest days as a startup and has been refined every year since. (Along the way, it has produced some of our most valuable innovations and biggest wins.) You can think of The Green Machine as a process of continuous improvement through small changes. When a small change improves metrics, we make more changes like that.
> In its most basic form, the Green Machine goes like this: gather excellent people, give them space to experiment, and then double down on what works.
> If you're working on something, and you're stuck, check it against these six steps. Maybe it's faltering because you didn't think carefully enough about your team, or because you don’t have the proper feedback loops. The Green Machine model can help just about any project get on track.
> 
> 
> The Green Machine: Six Steps 
> 
> 1. Staff It with Great People
> 
> Great experiments require exceptional teams who can quickly brainstorm ideas, execute, and pivot on a dime. This is why we set such a high bar in hiring and invest so much in our people. We like to keep teams lean and scrappy to start, only adding more people once we see success.
> 
> 2. Define Success
> 
> We always want to set clear, measurable goals—whether it’s DAUs, bookings, or social impressions. But metrics aren’t always available for early-stage projects. In that case, we define the best available qualitative goals, iterate toward clarity, and keep an eye out for any useful signals.
> 
> 3. Set Guardrails and Think Long-Term
>    
> We use guardrails to ensure our work benefits both Duolingo and our learners over the long term. This aligns with our core principle, Take the Long View. Thoughtful guardrails help us focus on sustainable, meaningful growth, ensuring that each experiment serves a greater purpose.
> 
> 4. Build the Thing and Set Up Feedback Loops
>    
> The fastest way to create something excellent isn’t through abstract discussions. Just start building, and create the right continuous feedback loops. This feedback comes from both quantitative (A/B test results, social impressions, efficacy research) and qualitative sources (extensive dogfooding). Early- stage projects typically lean more heavily on qualitative feedback before shifting to more data-driven metrics.
> 
> 5. Execute with Urgency and Excellence
> 
> Because of the compounding nature of smaller improvements, there is a huge cost to moving slowly. But moving too fast can also lead to sloppy outcomes. In step five, we work to continuously (and urgently) ship work that meets our bar.
> 
> 6. Double Down on What Works, Stop What Doesn’t
> 
> When something is working, we allocate more resources and keep working on it (sometimes for years). But we need to be comfortable sunsetting projects or even entire products that don’t demonstrate success.
> 
> > ⚠ Part of the Plan
> > 
> > Crucially, the Green Machine is not a replacement for planning. We still have quarterly OKRs, annual goals, and a long-range financial plan. The difference is that we don’t rely on multi-year roadmaps for the app.

---

### 詞彙表

* Bookings

我們用此來表示使用者透過 Duolingo 訂閱、應用內購買、DET 購買以及廣告網絡所帶來的收入總額。

* DAUs

每日活躍使用者。指每天使用 Duolingo（跨 iOS、Android 及網站）的獨立使用者數，是我們追蹤產品表現最重要的指標之一。

* DET

Duolingo 英語測試——我們的第二大產品，用於證明英語能力的認證考試，主要用於滿足大學國際招生需求。

* Dogfooding

指 Duolingo 團隊成員親自測試產品功能的行為。

* Duo

Duo 誕生於⋯⋯

* Duoversary

每年我們會在匹茲堡召集全體員工，共同慶祝 Duolingo 對外上線的周年紀念（2012年6月19日）。

* Experiments

測試哪些方法有效、哪些無效的實驗；A/B 測試則是同時比較兩個或多個方案的一種實驗方式。

* Go, Go, Go!

當你做對事時，Luis 會大聲喊出的口號。

* Juicy

Duolingo 的視覺設計系統，比以前更圓潤、更友善、更生動。

* MAUs

每月活躍使用者，指每月參與 Duolingo 的獨立使用者數。

* Nuo

一隻充滿才華、眼神明亮的貓頭鷹，會在加入 Duolingo 的前 90 天內提出許多問題。

* OKRs

目標與關鍵成果，一種由 Intel 於 1970 年代開發的目標設定模式；在 Duolingo，我們每季制定團隊 OKRs，每年制定公司 OKRs。

* Parliament

貓頭鷹的聚會，也是我們每週的全員大會（通常在星期一召開）。

* Pittsburgh

傳說中位於三條河流匯聚處的城市，被認為是 Duo 的發源地，同時也是我們的總部所在地！

* PR

產品審查是決定 app 改動是否獲得批准的會議，由產品團隊主持，但任何人都可以旁聽！（其他可能的意思：公共關係 Public Relations、Pull Request。）

* SLT

Senior Leadership Team，由公司內的所有副總裁（VPs）及以上管理層組成，有時還會有幾隻迷路的貓頭鷹。

* Subscribers

指付費訂閱 Duolingo 任一付費方案的使用者。

> ### Glossary
> * Bookings
> 
> We use bookings to indicate the amount of money we earn from users on subscriptions to Duolingo, in-app purchases, DET purchases, and advertising networks.
> 
> * DAUs
> 
> Daily Active Users. The number of individuals using Duolingo every day across iOS, Android, and the website. DAUs is one of the most important metrics we track, and tells us how well our products are doing.
> 
> * DET
>   
> The Duolingo English Test—our second major product. An adaptive certification test used to demonstrate English proficiency. Used primarily to meet international admissions requirements for universities.
> 
> * Dogfooding
> 
> When Duos test features of the product themselves.
> 
> * Duo
> 
> Duo was created in a ...
> 
> * Duoversary
> 
> Once a year, we gather the entire company in Pittsburgh to celebrate the anniversary of launching Duolingo to the public: June 19, 2012.
> 
> * Experiments
>   
> Tests to see what works and what doesn’t. A/B tests are a specific type of experiment where we simultaneously run two or more options against one another.
> 
> * Go, Go, Go!
>   
> Something Luis yells when you’re doing something right.
> 
> * Juicy
> 
> Duolingo’s visual design system. Plumper, friendlier, and juicier than it used to be.
> 
> * MAUs
> 
> Monthly Active Users. Number of unique users who engage with Duolingo every month.
> 
> * Nuo
>   
> Brilliant, bright-eyed owl who asks a ton of questions in their first 90 days of working at Duolingo.
> 
> * OKRs
>   
> Objectives and Key Results. A model for goal-setting originally developed at Intel in the 1970s. Here at Duolingo, we set team OKRs every quarter and company OKRs once a year.
> 
> * Parliament
>   
> A gathering of owls. Also, our weekly all-hands meeting—usually on Mondays.
> 
> * Pittsburgh
>   
> Fabled city at the confluence of three rivers said to be the birthplace of Duo. Also, our HQ!
> 
> * PR
> 
> Product Review—the meeting where we green-light every change to the app. Led by the Product Org, but anyone can listen in! (Alternative meanings: Public Relations, and Pull Request.)
> 
> * SLT
> 
> The Senior Leadership Team—consisting of all VPs and above at the company. And a few stray owls.
> 
> * Subscribers
> 
> Users who pay for access to any Duolingo paid subscription offering.
> 
