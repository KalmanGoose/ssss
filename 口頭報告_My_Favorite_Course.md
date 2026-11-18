# 課堂活動 (16+2) 個人口頭報告：My Favorite Course（去 AI 味＋完整課本完成式版）

> **報告主題**：*My Favorite Course: Introduction to Generative AI and Machine Learning*（臺大李宏毅教授《生成式人工智慧與機器學習導論》）
> **這版同時達成 4 大目標**：
> 1. **完整涵蓋課本 Unit 2「現在完成式」7 大關鍵字**：自然融入 **`ever`、`never`、`just`、`already`、`yet`、`for`、`since`**，加上 Unit 2.3 **`make mistakes / do your best`**。
> 2. **保留 Unit 3「過去完成式」＋ 6 句假設／條件句**：涵蓋 **`had been / had thought / had never had`**，以及 `unless`、`if`、`when`、與過去／現在相反假設句。
> 3. **去 AI 味自然口語**：全篇使用縮寫（Contractions）、長短句交錯、無 *To sum up / Moreover* 等僵硬作文詞，並自然唸出 **Artificial Intelligence** 與 **Large Language Models** 全名。
> 4. **簡報圖片全嵌死**：搭配 [slides.html](file:///Users/ethanchen/Desktop/英文/slides.html)（含真實課程封面、魔法師 vs. 魔術師、找函式 3 步驟、真實 Loss Curve、LLM 流程圖與 HW5／HW9 實作圖）。

---

## 壹、 純英文逐字稿（上台直接唸，無多餘標記）

### 【Slide 1】
Hi everyone, and Professor.
Quick question—have you ever used ChatGPT?
Today I want to talk about my favorite class: *Introduction to Generative AI and Machine Learning* by Professor Hung-yi Lee at NTU.
Most of us use Artificial Intelligence every day.
But here's the thing he said on day one: unless you know how it actually works, you're just a user. If you understand the ideas behind it, you can build things yourself.

### 【Slide 2】
Honestly, before I found this class, Artificial Intelligence had been a total mystery to me.
I had thought machine learning was just scary math.
If I hadn't watched his videos, I probably wouldn't have touched this field at all.
I've followed his course for a few months now—and since September, I've already learned so much.

### 【Slide 3】
Why do I like his teaching? He doesn't throw dry formulas at you.
Instead, he turns the whole thing into three simple steps with funny cartoons:
first, decide what "good" means with a loss function;
next, pick a model;
then, use gradient descent to slowly find the best answer.
Pretty simple, right?

### 【Slide 4】
Look at this loss curve from class.
When you train a model, if the line goes down like this, it means the computer is actually learning.
If the line gets stuck and stays flat, something is off—so you tweak your settings and try again.
You'll definitely make mistakes at first—that's normal, you just do your best and fix them step by step.

### 【Slide 5】
He also connects these basics straight to modern Artificial Intelligence—like how Large Language Models learn from huge text, and how image models make pictures.
Plus, he's put every single lecture on YouTube for free.
Even if you've never studied coding before, or you've just started learning, you can still pick it up anytime.

### 【Slide 6】
Before this class, I had never had the chance to train a real model myself.
My first few tries failed, and yeah, I wanted to quit.
But I didn't give up.
If you keep testing your code, you'll end up building cool stuff—like predicting game ratings or customizing AI images.
If I had more time today, I'd show you the whole demo live!

### 【Slide 7】
That's why this class means a lot to me—it's clear, fun, and hands-on.
I haven't finished all the homework yet, but I'm going to keep practicing next semester and build more projects.
My last slide has all the references I used.
Thanks for listening!

### 【Slide 8】
*(切換到 References 頁，微笑點頭收尾即可)*

---

## 貳、 中英文逐句對照（含課本完成式／文法標記）

### 【Slide 1】
* Hi everyone, and Professor.
  > 嗨，各位同學跟教授好。
* Quick question—**have you ever used** ChatGPT? `【Unit 2.2 現在完成式：ever】`
  > 先問大家一個問題——你們曾經用過 ChatGPT 嗎？
* Today I want to talk about my favorite class: *Introduction to Generative AI and Machine Learning* by Professor Hung-yi Lee at NTU.
  > 今天我想聊一門我最喜歡的課：臺大李宏毅教授的《生成式人工智慧與機器學習導論》。
* Most of us use Artificial Intelligence every day.
  > 我們大多數人每天都在用人工智慧。
* But here's the thing he said on day one: **unless** you know how it actually works, you're just a user. **If** you understand the ideas behind it, you can build things yourself. `【Unit 4.4 條件句：unless / if】`
  > 但教授在第一天就點出一件事：除非你知道它背後怎麼運作，否則你永遠只是個使用者；只要你懂原理，你也能自己動手做東西。

### 【Slide 2】
* Honestly, before I found this class, Artificial Intelligence **had been** a total mystery to me. `【課綱：had been】`
  > 老實說，在找到這門課以前，人工智慧對我來說完全是個謎。
* I **had thought** machine learning was just scary math. `【Unit 3 過去完成式：had + p.p.】`
  > 我以前一直以為機器學習全都是很可怕的數學。
* **If** I **hadn't watched** his videos, I probably **wouldn't have touched** this field at all. `【假設語氣 Type 3：與過去事實相反】`
  > 如果我當初沒看他的影片，我大概根本不會碰這個領域。
* **I've followed** his course **for** a few months now—and **since** September, **I've already learned** so much. `【Unit 2.2 & 2.4 現在完成式：for / since / already】`
  > 我已經追蹤這門課好幾個月了——而且從九月到現在，我已經學到超多。

### 【Slide 3】
* Why do I like his teaching? He doesn't throw dry formulas at you.
  > 我為什麼喜歡他的教法？因為他不會直接丟一堆枯燥的公式給你。
* Instead, he turns the whole thing into three simple steps with funny cartoons:
  > 相反地，他用好笑的漫畫把整件事變成三個簡單步驟：
* first, decide what "good" means with a loss function;
  > 第一，用 Loss Function 決定什麼叫做「好」；
* next, pick a model;
  > 接著，挑一個模型；
* then, use gradient descent to slowly find the best answer.
  > 然後，用梯度下降法慢慢找出最佳解。
* Pretty simple, right?
  > 很直覺吧？

### 【Slide 4】
* Look at this loss curve from class.
  > 你看課堂上這張 Loss 曲線圖。
* **When** you train a model, **if** the line goes down like this, it means the computer is actually learning. `【Unit 4.4：when + if】`
  > 當你在訓練模型時，如果線像這樣往下降，代表電腦真的在學習。
* **If** the line gets stuck and stays flat, something is off—so you tweak your settings and try again. `【條件句：if】`
  > 如果線卡住不動變平了，就代表哪裡怪怪的——這時就微調設定再試一次。
* You'll definitely **make mistakes** at first—that's normal, you just **do your best** and fix them step by step. `【Unit 2.3 Word Friends：make mistakes / do your best】`
  > 一開始一定會出錯——這很正常，只要盡力做並一步步修正就好。

### 【Slide 5】
* He also connects these basics straight to modern Artificial Intelligence—like how Large Language Models learn from huge text, and how image models make pictures.
  > 他也會把這些基礎直接連到現代人工智慧——像是大型語言模型怎麼從海量文字學習，以及影像模型怎麼生圖。
* Plus, **he's put** every single lecture on YouTube for free. `【現在完成式：has put】`
  > 而且他把每一堂課都免費放在 YouTube 上。
* Even if **you've never studied** coding before, or **you've just started** learning, you can still pick it up anytime. `【Unit 2.2 現在完成式：never / just】`
  > 就算你以前從沒學過寫程式，或是才剛開始學，隨時都還是能上手。

### 【Slide 6】
* Before this class, I **had never had** the chance to train a real model myself. `【課綱：had had】`
  > 上這門課以前，我從來沒機會自己訓練一個真正的模型。
* My first few tries failed, and yeah, I wanted to quit.
  > 前幾次嘗試都失敗，老實講我那時超想放棄。
* But I didn't **give up**. `【Unit 4.3 片語動詞：give up】`
  > 但我撐下來沒有放棄。
* **If** you keep testing your code, you'll **end up** building cool stuff—like predicting game ratings or customizing AI images. `【Unit 4.4 First Conditional + Unit 4.3 end up】`
  > 只要你不斷測試程式，最後就能做出很酷的東西——像是預測遊戲評分，或客製化 AI 生成圖片。
* **If** I **had** more time today, I**'d show** you the whole demo live! `【假設語氣 Type 2：與現在事實相反】`
  > 如果今天時間更充裕的話，我就直接現場展示整個作品給大家看！

### 【Slide 7】
* That's why this class means a lot to me—it's clear, fun, and hands-on.
  > 這就是為什麼這門課對我意義很大——它清楚、有趣，又能動手實作。
* **I haven't finished** all the homework **yet**, but I'm going to keep practicing next semester and build more projects. `【Unit 2.2 現在完成式：yet ＋ Unit 4.2 未來計畫】`
  > 我雖然還沒做完所有的作業，但我下學期會繼續練習，做出更多專題。
* My last slide has all the references I used.
  > 最後一張投影片是我參考的資料來源。
* Thanks for listening!
  > 謝謝大家！

---

## 參、 課本 Unit 2「現在完成式」7 大關鍵字總盤點

| 課本關鍵字 | 用法說明 | 本講稿實際句子 |
| :--- | :--- | :--- |
| **`ever`** | 問「曾經……過嗎？」（Slide 1） | *Quick question—**have you ever used** ChatGPT?* |
| **`for`** | 接「一段時間」（Slide 2） | *I'**ve followed** his course **for** a few months now...* |
| **`since`** | 接「過去某時間點」（Slide 2） | *...and **since** September, I've already learned so much.* |
| **`already`** | 「已經」（Slide 2） | *...I'**ve already learned** so much.* |
| **`never`** | 「從未」（Slide 5） | *Even if you'**ve never studied** coding before...* |
| **`just`** | 「剛剛」（Slide 5） | *...or you'**ve just started** learning...* |
| **`yet`** | 「尚未」（否定／疑問句尾，Slide 7） | *I **haven't finished** all the homework **yet**...* |
