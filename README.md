## Hi, I'm Harshit 👋

AI & Robotics Engineering student at **Chulalongkorn University**, Bangkok.
I build AI agents that take boring real-world tasks off people's hands, and I build them with AI coding tools (Claude Code, Codex).

---

## 👉 Start here: Cally

**An AI agent that phones repair shops for you.** Tell it what's broken, it calls the shops near you for a price, and you see the cheapest first.

[![Open Cally (live app)](https://img.shields.io/badge/▶%20Open%20Cally-live%20app-5b21b6?style=for-the-badge)](https://cally-repair.vercel.app)
[![See the code](https://img.shields.io/badge/See%20the%20code-GitHub-24292f?style=for-the-badge&logo=github)](https://github.com/axm12345/cally)

| 1. Say what's broken | 2. Cally calls nearby shops | 3. Cheapest first |
|:---:|:---:|:---:|
| <img src="images/cally-home.png" width="220" alt="Pick what's broken, or just say it"> | <img src="images/cally-calling.jpg" width="220" alt="AI agent talking to five repair shops"> | <img src="images/cally-results.jpg" width="220" alt="Prices compared, cheapest first"> |

**Try it in 1 minute** (best on a phone): open the app → tap **Cracked screen** → tap **Type instead** and write *"iPhone 13, need it today"* → tap **Yes, find me a shop**.
<sub>The public demo uses real shop listings, but the calls and prices are simulated, so no shop's phone actually rings.</sub>

---

## 💬 Also built: LINE auto-reply bot

**A LINE chatbot for small shops. It answers customers instantly in Thai or English, and hands the chat to a real person when it isn't sure.**

<table>
<tr>
<td width="290" valign="top">
<img src="images/line-bot-chat.png" width="270" alt="Customer asks opening hours, price in Thai and delivery; the bot answers each instantly">
<br><sub>Real replies from the bot's code, shown in a recreated LINE chat.</sub>
</td>
<td valign="top">
<b>How it decides what to say</b>
<ol>
<li><b>Keyword match</b> in English or Thai (<i>open, ราคา, deliver…</i>): instant, free, exact answer from the shop's info</li>
<li><b>No match:</b> Claude writes a reply, using <i>only</i> the shop's real info</li>
<li><b>Claude would have to guess:</b> it hands the chat to a human instead of making something up</li>
</ol>
<b>Why it matters:</b> small shops in Thailand get most customer questions on LINE, and when the owner is busy they go unanswered.
<br><br>
<b>Make it any shop's bot:</b> swap one data file (hours, menu, delivery zone).
<br><br>
<code>Python</code> <code>Flask</code> <code>LINE Messaging API</code> <code>Claude API</code>
<br><br>
<a href="https://github.com/axm12345/line-demo-cafe-bot"><img src="https://img.shields.io/badge/See%20the%20code-GitHub-24292f?style=for-the-badge&logo=github" alt="See the code"></a>
</td>
</tr>
</table>

---

## 📂 All my projects

🟢 Green button = a live app you can open and use right now.

| Project | What it does | Open it |
|---|---|---|
| 🔧 **Cally** | AI voice agent that calls repair shops and compares their prices for you | [![Live app](https://img.shields.io/badge/▶%20Live%20app-2ea043?style=for-the-badge)](https://cally-repair.vercel.app) [![Code](https://img.shields.io/badge/Code-555555?style=for-the-badge&logo=github)](https://github.com/axm12345/cally) |
| 💬 **LINE auto-reply bot** | Answers a small shop's customers on LINE in Thai or English, and hands off to a human when it's unsure | [![Code](https://img.shields.io/badge/Code-555555?style=for-the-badge&logo=github)](https://github.com/axm12345/line-demo-cafe-bot) |
| 📄 **CV Generator** | Build a CV in your browser with live preview, 4 templates and PDF download | [![Live app](https://img.shields.io/badge/▶%20Live%20app-2ea043?style=for-the-badge)](https://axm12345.github.io/cv-generator/) [![Code](https://img.shields.io/badge/Code-555555?style=for-the-badge&logo=github)](https://github.com/axm12345/cv-generator) |
| 📈 **SwingBot** | Python trading bot with a backtester, automated tests and strict safety limits (practice account by default) | [![Code](https://img.shields.io/badge/Code-555555?style=for-the-badge&logo=github)](https://github.com/axm12345/swingbot) |
| 🖥️ **PC Builder Tycoon** | Roblox game (playable v1 prototype): buy parts, build PCs and complete client jobs | [![Code](https://img.shields.io/badge/Code-555555?style=for-the-badge&logo=github)](https://github.com/axm12345/pc-builder-tycoon) |
| 🌱 **Learning projects** | My first Python programs and a playful interactive web page | [![Code](https://img.shields.io/badge/Code-555555?style=for-the-badge&logo=github)](https://github.com/axm12345/learning-projects) |

---

**Tools I use:** TypeScript · Next.js · JavaScript · Python · Flask · Lua (Roblox) · Claude API · ElevenLabs voice agents · Vercel
**Currently learning:** SQL, and building AI agents that work reliably without a person watching them
