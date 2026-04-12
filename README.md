# 🌿 Greenearth Organic — Invoice Manager

![Greenearth](https://img.shields.io/badge/Greenearth%20Organic-Invoice%20Portal-success?style=for-the-badge)
![Offline](https://img.shields.io/badge/Offline-Supported-blue?style=for-the-badge)
![No DB](https://img.shields.io/badge/Local-Storage-orange?style=for-the-badge)
![No Login](https://img.shields.io/badge/Login-Removed-red?style=for-the-badge)

A premium, frontend-only Web Application designed specifically for **Greenearth Organic** to generate tax-compliant GST invoices and share them instantly via PDF or WhatsApp — directly from the browser, no server needed.

---

## 🚀 Features

*   ⚡ **Direct Access — No Login Required:** Opens straight to the Dashboard. No username or password needed.
*   📡 **100% Offline Capable:** All data is stored in the browser's `localStorage`. No internet required to view or create invoices.
*   📱 **Mobile Optimised & App-like:** Can be saved to your phone's Home Screen and runs like a native app.
*   🧾 **GST Tax Invoice Generator:** Create professional, tax-compliant invoices with GST calculation (0%, 5%, 12%, 18%).
*   💬 **One-Click WhatsApp & PDF Sharing:** Share invoices directly via WhatsApp or download as PDF.
*   📦 **Inventory & Stock Management:** Track products, stock levels, minimum stock alerts, and rates.
*   👥 **Customer Directory:** Auto-saves customers from invoices with total spend tracking.
*   📊 **Analytics & Reports:** Monthly sales chart, top products, and top customers.
*   ⚙️ **Settings Panel:** Update company name, GSTIN, PAN, address, logo, and terms & conditions.
*   💾 **JSON Backup & Restore:** Export all data as a JSON file for backup.

---

## 💻 Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | App structure & layout |
| **TailwindCSS (CDN)** | Rapid, responsive styling |
| **Vanilla JS (ES6)** | All business logic, no frameworks |
| **html2canvas + jsPDF** | Client-side PDF generation |
| **LocalStorage** | Persistent offline database |

---

## 🌐 Live Deployment

🔗 **Live App:** [https://greenearth-invoice-app-2026.netlify.app](https://greenearth-invoice-app-2026.netlify.app)

> Auto-deployed via **Netlify** on every `git push` to the `main` branch.

---

## 📱 How to Install on Mobile (Offline Mode)

1. Open the Live Site URL in Chrome or Safari on your phone.
2. Tap the browser **Menu (⋮)** → click **"Add to Home Screen"**.
3. The Invoice Generator will be installed on your Home Screen and works **even without internet**!

---

## 📋 How to Use

1. Open the app — it goes directly to the **Dashboard**.
2. Click **➕ New Invoice** to create a GST invoice.
3. Select customer, add products, choose GST %, save invoice.
4. Share via **WhatsApp** or download as **PDF**.
5. Manage stock in **Inventory**, view analytics in **Reports**.
6. Update company info in **Settings**.

---

## ⚠️ Disclaimer

This project uses `localStorage` for data persistence. Clearing your browser cache/storage will erase all data. Use the **Export JSON Backup** option in Settings regularly to keep your data safe.

---

*Built with ❤️ for Greenearth Organic — Improving Agriculture, Improving Lives 🌿*
