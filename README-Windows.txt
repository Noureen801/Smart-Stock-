SmartStock — Sufi Akram Cloth House
Windows Local-Run Package
================================

WHAT THIS IS
------------
A complete, functional inventory & sales app for Sufi Akram Cloth
House. No internet, no install, no Python needed. Just open the
HTML file in a browser on your Windows PC.

FILES IN THIS FOLDER
--------------------
  SmartStock-Windows.html  - the whole app (open this)
  run.bat                  - double-click this to open the app
  README-Windows.txt       - this file

HOW TO RUN ON WINDOWS
---------------------
1) Copy this whole folder to your Windows PC, e.g.
   C:\SmartStock\  (or Desktop\SmartStock\).

2) Double-click run.bat
   - or double-click SmartStock-Windows.html directly.
   It opens in your default browser (Chrome or Edge recommended).

3) FIRST LAUNCH — SET YOUR PIN
   - The app asks you to set a Staff PIN (4-8 digits).
   - There is NO default PIN. Choose one only you know.
   - The app locks on every load / reload. Enter the PIN to unlock.
   - Use the Lock button (top right) when you leave the counter.
   - Change the PIN in Settings > Change Staff PIN (needs current PIN).
   - The PIN cannot be removed.

4) ADD YOUR STOCK (or try samples first)
   - Settings > "Load Sample Cloth Data" adds 8 sample products
     (Men's Lawn Suit, Women's Lawn 3pc, Bridal Silk, bed sheets, etc.)
     You can edit or delete them.
   - Or go to Products > Add Product with your real stock.
   - Categories: Men's Clothing, Women's Clothing, Bridal Fabrics,
     Bed Sheets, Other Textiles. Stock is in pieces or meters.

5) MAKE A TEST SALE
   - Go to New Sale, pick a product, enter quantity, customer name
     and payment (Cash / JazzCash / Bank Transfer).
   - The app blocks the sale if quantity is more than stock.
   - Stock is deducted immediately and an invoice is generated,
     e.g. INV-20261113-0001. Use Print Invoice to print it.
   - Check Dashboard: Sales Today and stock should update.
   - In Sales, deleting a sale restores its stock.

6) REPORTS & DASHBOARD
   - Dashboard: total products, total stock, stock value at cost
     and at sale price, sales today / last 7 days / this month,
     low-stock alerts, recent sales, 14-day chart.
   - Reports: Daily / Weekly / Monthly tabs — revenue, estimated
     profit (sale price minus cost), top products, category and
     payment breakdowns.

6b) PROFIT & LOSS (new)
   - Top menu > Profit & Loss. Daily / Weekly / Monthly tabs, or
     pick a custom date range and Apply.
   - Financial overview cards: Total Revenue, Total COGS (actual
     cost of products sold), Gross Profit, Total Business Expenses,
     Net Profit, and Gross Profit Margin.
     Revenue = total sales. COGS = quantity sold x purchase cost
     frozen at the time of sale. Gross = Revenue - COGS.
     Net = Gross - Expenses. Margin = Gross / Revenue x 100.
   - Changing a product's cost price later does NOT change past
     sales: each sale stores the cost at sale time. Unsold stock
     is never counted as COGS.
   - Product-wise Profit table and Most Profitable Products list.
   - Charts: monthly revenue vs gross/net profit (last 6 months),
     gross vs net profit for the selected period, and expense
     breakdown by category.
   - Expenses: in Profit & Loss, Add Expense with date, category
     (Rent, Electricity, Salaries, Transportation, Other),
     description and amount. Edit or Delete an expense in the
     Expenses in Period table — totals update at once. Each
     expense is counted once, only in its own date period.
   - Products list now also shows Profit / Unit (sale - cost)
     for piece and meter products.
   - Expenses are saved with your backup (Export Backup JSON).

7) BACK UP REGULARLY
   - Settings > Export Backup (JSON) — save the file somewhere safe.
   - Settings > Import Backup — restore it on the same or another PC.
   - Settings > Export Sales CSV — open sales in Excel.
   - Do a backup weekly, or after a busy day.

IMPORTANT — WHERE YOUR DATA LIVES
----------------------------------
Data is stored in the browser's localStorage on THAT PC, under the
key smartstock_db_v1. That means:
  - Use the SAME browser and SAME Windows user profile every time.
  - Clearing browser data / using a different browser will hide
    your data — restore it from an Export Backup.
  - Do not use Private / Incognito mode for daily use.
  - Keep the Export Backup file in a safe place (USB / Google Drive).

TROUBLESHOOTING
---------------
  - App asks for PIN every time: that is by design. Enter your PIN.
  - Forgot PIN: there is no recovery. Use Settings > Clear All Data
    only as a last resort — it erases everything. Restore from backup
    afterwards if you have one.
  - File opens as text / downloads instead of opening: right-click
    SmartStock-Windows.html > Open with > Chrome / Edge.
  - Prices show in Rs and dates in PKT format.

Shop: Sufi Akram Cloth House
User: Noureen Aslam
