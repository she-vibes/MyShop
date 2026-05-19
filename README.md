My Shop Records
A simple, offline-first retail bookkeeping app for small shop owners — built as a single HTML
file with no frameworks, no installs, and no internet required.

What It Does
My Shop Records helps a shop owner track the money coming in and going out every day:
Log sales — record what was sold and for how much
Log expenses — track restocking costs and daily overheads
See today’s profit — sales minus expenses, calculated instantly
Manage products — keep a reusable price list to speed up entry
All data saved locally — nothing leaves the device; works offline

Who It’s For
Small, independent shop owners — particularly those who:
Are not comfortable with complex accounting software
Use a budget Android or iOS phone as their primary device
Want something faster than a paper notebook but simpler than a spreadsheet
Have no reliable internet connection throughout the day

How to Run It Locally
No installs. No terminal commands. No npm.
1. Download or clone this repository
git clone https://github.com/your-username/my-shop-records.git

2. Open the project folder
3. Double-click index.html
4. It opens in your browser — that’s it
To edit the code, open index.html in VS Code or github.dev.
Tip for mobile: Upload index.html to any static host (GitHub Pages, Netlify Drop) and

open the URL on your phone. Tap Add to Home Screen in Safari or Chrome for a full-
screen, app-like experience.

Data & Privacy
All data is stored in your browser’s localStorage under these keys:
Key Contents
msr_v1_sales All recorded sales
msr_v1_expenses All recorded expenses
msr_v1_items Your product price list
No data is sent anywhere. No account needed. No tracking.
Important: If you clear your browser data or switch phones, your records will be lost.
Export or back up regularly (see Coming Next).

Tech Stack

Layer Choice Why
Language Vanilla HTML, CSS,

JavaScript No build step; works on any device
Storage localStorage Offline, instant, no backend needed
Hosting Any static host or local file Zero cost, zero setup
Frameworks None Keeps the file small and fast on budget

phones

Coming Next
Google Sheets sync — back up all records to Google Drive automatically
Daily WhatsApp summary — receive today’s profit report at end of day
UPI payment auto-logging — detect incoming GPay/PhonePe payments as sales
Barcode scanner — point camera at a product to auto-fill name and price
CSV export — download records as a spreadsheet for your accountant
Date filter — view sales and expenses by day, week, or month
Multi-currency support — switch between ₹, ₱, and other currencies

Contributing
This is a personal tool built for a specific user. If you have a suggestion or spot a bug, open
an issue or submit a pull request. Keep it simple — no frameworks, no dependencies.

License
MIT — free to use, modify, and share.
