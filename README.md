# FireFest POS – Getränke & Pfand Kasse

A simple, touch-friendly Point of Sale (POS) web app for iPad, designed for use at fire brigade festivals or similar events.  
It helps volunteers quickly sell drinks, handle Pfand (deposit) charges, and calculate change.

## ✨ Features
- **Three drinks**:
    - Wasser → 1,50 €
    - Softdrink → 3,00 €
    - Bier → 5,00 €
- **Automatic Pfand** per drink:
    - Wasser & Softdrink: +1 € Pfand
    - Bier: +2 € Pfand
- **Manual Pfand buttons**: +1 € and +2 € for flexibility
- **Pfand-Rückgabe**: subtract 1 € or 2 € when glasses/bottles are returned
- **Cash input buttons**: 20, 10, 5, 2, 1, 0.50 €
- **Automatic calculation** of:
    - Drinks sum
    - Pfand
    - Pfand-Rückgabe
    - Total due
    - Amount received
    - Change
    - Missing amount
- **Easy corrections**: long-press any button to subtract instead of add
- **Reset order** and **Exact balance** (auto-fill received amount)

## 📱 Usage
1. Open the app on an iPad in Safari.
2. Tap **Share → Add to Home Screen** to run it fullscreen like an app.
3. Use the large buttons to add drinks and Pfand.
4. Enter customer’s cash using quick-amount buttons.
5. See the live calculation of what’s due, received, change, and missing.
6. Tap **Neue Bestellung** to reset for the next customer.

## 🛠️ Tech Stack
- HTML5
- CSS3 (responsive, light mode)
- Vanilla JavaScript (no frameworks, runs fully offline)

## 🚀 Deployment
1. Save the file as `index.html`.
2. Host it on any static server (e.g., GitHub Pages, Netlify) or run locally.
3. Open it on the device — no backend required.

## 📄 License
MIT License