# Tana Investing — Sales & Inventory

A lightweight, mobile-friendly sales and inventory tracker for a home-based furniture and household shop. It runs in your browser—no installation, account, or server required.

## Get started

1. Open `index.html` in a modern browser.
2. Select **Inventory → Add product** to enter products, prices, quantities, categories, and low-stock alert levels.
3. Select **Record a sale** to log a transaction. The sale total is calculated automatically and available stock is reduced immediately.
4. Check **Overview** for today's and this month's sales, current stock, low-stock products, and recent transactions.
5. Export your inventory or transaction history as CSV from the Inventory or Sales page.

## Included

- Product creation, editing, search, category and stock-level filters, and deletion
- Low-stock alerts based on a configurable per-product threshold
- Sales with quantity validation, payment method, calculated totals, and automatic stock updates
- Dashboard metrics and searchable transaction history
- CSV exports for inventory and sales
- Responsive layout for desktop and mobile
- Browser `localStorage` persistence

## Notes

- Data stays in the browser and on the device where it was entered. It is not synced between devices or shared with other users.
- Export CSV files regularly as a backup. Clearing browser site data can remove saved records.
- Prices use the browser's default USD currency formatting. Change the `currency: 'USD'` setting in `index.html` if you want another currency code.
