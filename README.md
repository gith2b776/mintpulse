MintPulse Desktop

A privacy-first, single-file personal financial dashboard that turns bank and credit card exports into an interactive Mint-style overview—running 100% locally in your browser with zero servers, accounts, or subscriptions.

Live Web App: https://gith2b776.github.io/mintpulse/

Source Code: https://github.com/gith2b776/mintpulse

Features

Universal Statement Import: Drag and drop .csv, .xlsx, .xls, .ofx, .qfx, .tsv, or .pdf files—or paste raw statement rows directly from your online banking portal.

Smart Column Mapping & Live Preview: Automatically detects Date, Merchant/Description, Amount (or split Debit/Credit columns), and sign conventions with an interactive preview before importing.

400+ Merchant & Keyword Auto-Categorizer: Cleans payment processor noise (POS, ACH, SQ *, TST*, store numbers) and categorizes transactions automatically. Re-categorizing any merchant once saves a custom rule and updates all matching transactions.

Interactive Charts & Click-to-Inspect Drill-Downs:

Cash Flow Over Time (Income vs. Spending)

Spending by Category Donut & Progress Breakdown

Net Income Over Time (Period Net & Cumulative Net modes)

Cumulative Spending Trajectory & Top Merchants Leaderboard

Day-of-Week Spending, Ticket Size Distribution, Category Trend Explorer, and Recurring Bills Radar

Click any bar, slice, or point on any chart to inspect, sort, or re-categorize the exact underlying transactions.

Flexible Timeframe & Multi-Account Filtering: View all history or step cleanly by Month, Quarter, Year, or Custom date range across combined credit card and checking accounts.

Comprehensive 14-Column CSV Export: Download your cleaned, categorized ledger (either all transactions or your active filtered view) at any time.

Automatic Dark & Light Mode: Syncs automatically with your computer's system theme (System, Light, or Dark).

Run Completely Offline (Desktop Mode)

Because MintPulse Desktop is packaged as a single self-contained index.html file, you do not need to use the hosted link if you prefer to run it offline:

Download index.html to your computer.

Double-click index.html to open it locally in Chrome, Edge, Safari, or Firefox.

Optional: Click Load Sample Dataset on the welcome screen to preview the dashboard before uploading your own statements.

Privacy & Security

Zero Server Uploads: All CSV, Excel, OFX, and PDF parsing happens entirely inside your browser's JavaScript runtime. Your financial files never leave your machine.

Local Storage Only: Imported transactions and custom rules are saved strictly in your browser's localStorage so they persist between sessions on your device, and can be wiped anytime via Reset / clear data in the sidebar.

Single-File Transparency: All application logic lives in index.html so anyone can inspect the source code 
