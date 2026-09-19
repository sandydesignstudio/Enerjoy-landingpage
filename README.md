# Enerjoy Solar - Landing Page

Official, high-converting premium landing page for **Enerjoy Solar**, featuring custom rooftop solar solutions for Home, Commercial, and Industrial properties.

## 🌟 Key Features
- **Modern High-Contrast Aesthetic**: Custom brand colors (`#113d3e` Deep Forest Emerald Green and `#ef8329` Sunburst Orange).
- **Official Branding**: Integrated official Enerjoy Solar logo and leadership photography (Er. Aravind J, Founder & CEO).
- **HD Real Architectural Photography**: Realistic rooftop solar panel visuals for Hero section, Home Solar, Commercial Solar, and Industrial Solar cards.
- **Interactive Solar Sizing Calculator**: Dynamic kW, monthly generation units, and roof area estimation sliders.
- **Lead Capture & Google Sheet Integration**: Automatically submits leads to Google Sheets via Google Apps Script Web App endpoints with localStorage backup.
- **Personalized Thank You Confirmation Modal**: Instant feedback upon lead submission with 1-click WhatsApp and phone call actions.

## 🚀 Quick Setup & Usage
Simply open `index.html` in any web browser or host using any HTTP server (e.g. `python3 -m http.server 8085` or Vercel/Netlify).

## 📊 Google Sheet Lead Setup
To connect form submissions to your Google Sheet:
1. Open your Google Sheet -> **Extensions** -> **Apps Script**.
2. Add the `doPost(e)` script function.
3. Deploy as **Web App** (Access: *Anyone*).
4. Paste the Web App URL into `GOOGLE_SHEET_URL` in `index.html`.

---
© 2026 Enerjoy Solar. All rights reserved.
