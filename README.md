
### 🐙 Cashflow Survival Days – "Duolingo for SME Cashflow"

**Live Demo:** https://amaningkwartengrebecca-eng.github.io/cashflow-survival-days/

---

### Why I built this

I built this because most founders I've spoken to don't understand their cashflow. Not because they're not capable but because no one ever taught them how to. They're busy building their business to truly consider its impact.Choosing to leave the numbers to their accountant and cross their fingers.

99% of UK businesses are SMEs. Late invoice payments cost £11bn a year. That's not just a figure - It's  real businesses going under and people losing their jobs.

I wanted to build something that actually helps. Something that turns cashflow from a spreadsheet nightmare into something people can see and understand. Something that might make it even juat a little less boring.

The education section (The quizzes tab on the MVP) will always be free. I don't care how big this becomes, that stays.

---

### 🚀 Features

- **Survival Days Dashboard** – Able to see cash runway in days (colour-coded with avatar feedback)
- **What-If Scenario Dropbox** – Simulating the impact of client delaying payments by (0/14/30 days)
- **Invoice Timeline (Table)** – Group invoices by month, edit them and see total amount lost
- **UK Statutory Interest Calculator** – Calculates 8% + BoE base rate on overdue invoices
- **Gamified Quizzes** – Earn XP, hearts, and coins (with heart regeneration)
- **Dark / Light Mode** – Jellyfish logo changes colour based on the choosen theme
- **Google Sheets Sync** – Import invoices from a published Google Sheet (CSV)
- **No Backend – Works Offline** – All data stored in your browser's localStorage (MVP)

---
### Google Sheets Setup (For Import)

Want to import your own invoices? Here's how:

1. **Create a Google Sheet** with these column headers (exactly as written, case-sensitive):

| Column | What it means |
| :--- | :--- |
| `Customer` | The client or customer name |
| `Invoice Date` | Date invoice was issued (format: DD/MM/YYYY) |
| `Due Date` | Date payment is due (format: DD/MM/YYYY) |
| `Amount` | Invoice amount (£) |
| `Paid` | Yes/No – has this been paid? |
| `Overdue` | Yes/No – is this overdue? |

2. **Publish the sheet to the web:**
   - File → Share → Publish to web
   - Copy the link (the one that ends with `?gid=0&single=true&output=csv`)

3. **Paste the link** into the Cashflow Survival Days import field and click "Load"

That's it. Your invoices will appear in the dashboard, and used for the survival days calculator.

> ⚠️ **Important:** Make sure your column headers match exactly and are Lower-Case. The import tool looks for these specific names. If you need a template, here's a template can copy (just click the link): [https://docs.google.com/spreadsheets/d/1-EzsW1401O3YoyWnbz-RZSnITB-UdkKTq8Eby9Xiens/copy]

---

### 🛠️ Tech Stack

- Vanilla JavaScript (ES6)
- Tailwind CSS
- HTML5 + CSS3
- localStorage for persistence
- Google Sheets API (CSV import)

---

### 📊 What I Learned

**The Most Difficult Aspect for Me**
Handling the Light and dark mode colour schemes. Not the logic, just getting the colours to actually look right in both modes without making everything look like a mess. It took me way longer than I want to admit. Also linking the Google Sheet import took a few hours. "simple" features are rarely simple to build.

**What surprised me**
How open founders were about their struggles. They'd just tell me, straight up, what they didn't understand. It felt like an open secret as everyone struggling with the same thing, but no one really talking about it.

**What stuck with me**
The transparency they showed me made me want to give that back which is why, the education section will always be free.

**The Name and the Jellyfish Logo**
I originally wanted to call it Tide (or Tyde)  because cashflow can consume businesses and indiviuals like a wave. But Survival Days stuck. It's about how many days you have left, like a ship sinking, it can be saved if caught early. Why the jellyfish? Their underestimated creature and extremely smart. Cashflow is the same, underestimated, incredibly important. The tagline "Cash Is King" came from my lecturer. As I've come to learn overtime, It's true.

**My Biggest Takeaway**
Asking people is always the right step. Conducting Research. Acting on initiative, a simple thought can change everything. All leading to positive outcomes, it just depends on how you spin them. The founders' feedback shaped everything, even the parts I didn't want to change.

---

### 🔮 What's Next (V1 Roadmap)

- User accounts + cloud sync (Supabase)
- Xero API integration (auto-import invoices)
- Team leaderboards & collaboration 
- Paid subscriptions (Beta at £5/mo, Launch at £9.99/mo)

---

### 🏗️ How to Run Locally

1. Download the `index.html` file
2. Open it in your browser
3. No server needed – everything works offline

---

### 📬 Contact Me

[LinkedIn](https://www.linkedin.com/in/rebecca-amaning-kwarteng-05a4b6283/) | [Email](Amaningkwartengrebecca@gmail.com)

---

### 📄 License

MIT – use it, fork it, build on it. Just don't sell it as your own.

