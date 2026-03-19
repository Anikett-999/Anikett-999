![logo](https://github.com/Anikett-999/Anikett-999/blob/main/Make%20your%20README.png)
<h1 align="center">Hi 👋, I'm Aniket Bedre</h1>
<h3 align="center">A passionate Software Developer from India</h3>
<img align="right" alt="coding" width=300 src="https://shorturl.at/ubgE7"
<p align="left"> <img src="https://komarev.com/ghpvc/?username=anikett-999&label=Profile%20views&color=0e75b6&style=flat" alt="anikett-999" /> </p>

- 📫 How to reach me **aniketbedre28@gmail.com**

- ⚡ Fun fact **I think I am not Funny**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/aniket-nagnath-bedre" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="aniket-nagnath-bedre" height="30" width="40" /></a>
<a href="https://fb.com/https://shorturl.at/zxrqg" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="https://shorturl.at/zxrqg" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.oracle.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=anikett-999&show_icons=true&locale=en&layout=compact" alt="anikett-999" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=anikett-999&show_icons=true&locale=en" alt="anikett-999" /></p>

## Notion Monthly Finance Tracker Workspace

Use this setup in Notion to track all monthly financial transactions in one place.

### Where to create it
- Open your **Notion app** (desktop/mobile/web).
- In the **left sidebar**, click **+ Add a page**.
- Create a new top-level page named **Finance HQ**.
- Everything below should be created **inside that Finance HQ page in Notion** (not in this GitHub repo).

### 1) Create a workspace page
- Create a top-level page: **Finance HQ**
- Add 3 sub-pages:
  - **Transactions**
  - **Monthly Dashboard**
  - **Budgets & Goals**

### 2) Build the Transactions database (table)
Create a full-page table named **Transactions** with these properties:

| Property | Type | Purpose |
|---|---|---|
| Date | Date | Transaction date |
| Description | Title | Merchant or note |
| Amount | Number (Currency) | Transaction value |
| Type | Select | Expense / Income / Transfer |
| Category | Select | Food, Rent, Bills, Salary, Travel, etc. |
| Account | Select | Cash, Bank, Credit Card, Wallet |
| Payment Mode | Select | UPI, Card, Net Banking, Cash |
| Month | Formula | Month bucket for reporting |
| Tags | Multi-select | Optional labels |
| Receipt | Files & media | Bill or invoice proof |

Use this formula for **Month**:
`formatDate(prop("Date"), "YYYY-MM")`

### 3) Add useful views
Inside **Transactions**, create these views:
- **All Transactions** (default table)
- **This Month** (filter Month = current month)
- **Expenses Only** (filter Type = Expense)
- **Income Only** (filter Type = Income)
- **By Category** (board grouped by Category)
- **Calendar View** (calendar by Date)

### 4) Create the Monthly Dashboard
On **Monthly Dashboard**:
- Add linked database of **Transactions**
- Create summary blocks:
  - **Total Income (Month)**
  - **Total Expense (Month)**
  - **Net Savings = Income - Expense**
- Add category breakdown (group by Category)
- Add top 5 biggest expenses (sort Amount descending, filter Type=Expense)

### 5) Build Budgets & Goals page
Create a second table named **Budgets**:
- Category (Title)
- Monthly Budget (Number)
- Month (Date or text YYYY-MM)
- Actual Spend (Rollup from Transactions)
- Remaining (Formula = Budget - Actual)
- Status (Formula: On Track / Overspent)

### 6) Weekly and monthly routine
- **Daily:** add every transaction immediately
- **Weekly:** review uncategorized transactions
- **Month-end:** duplicate month dashboard, close totals, set next month budgets

### Ready-to-copy transaction examples
| Date | Description | Amount | Type | Category | Account | Payment Mode |
|---|---|---:|---|---|---|---|
| 2026-03-01 | Salary Credit | 85000 | Income | Salary | Bank | Net Banking |
| 2026-03-03 | Grocery Store | 2400 | Expense | Food | Credit Card | Card |
| 2026-03-05 | Electricity Bill | 1800 | Expense | Bills | Bank | UPI |

This structure gives one clean Notion workspace for complete monthly financial tracking.
