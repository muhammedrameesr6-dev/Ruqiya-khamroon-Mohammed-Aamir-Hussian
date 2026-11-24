# Wedding & Nikah Invitation Website

A personalized, elegant wedding and Nikah invitation website for **Mohammed Aamir Hussain (B.E) & Ruqiya Khamroon (M.Sc)**.

---

## 💍 Event Summary

- **Groom**: Mohammed Aamir Hussain (B.E)
- **Bride**: Ruqiya Khamroon (M.Sc)
- **Date**: Saturday, 26 December 2026
- **Time**: 12:30 PM (Lunch thereafter)
- **Occasion**: Sacred Nikah Ceremony & Lunch Feast
- **Venue**: MS Community Hall, Near Sangam Theater Road, Mulbagal
- **Groom's Family**: Son of Late Abdul Basheer (Ex KSTDC) & Mrs. Sadiqa Khatoon (B.Com)
- **Bride's Family**: Daughter of Mr. Altaf Pasha & Mrs. Altaf Pasha
- **Invitation Hosted By**: Muthvali Abdul Rawoof Saheb & Family
- **Special Invitation**: KGN Group
- **Theme & Color Palette**: Royal Emerald Green & Warm Beige / Champagne Gold

---

## 📁 Project Structure

```text
├── index.html                 # Main invitation HTML page
├── couple.jpg                 # Hero and opening gate photograph
├── og.jpg                     # Open Graph preview card for social sharing
├── README.md                  # Project overview and guide
├── assets/
│   ├── images/
│   │   └── hero-bg.png        # Pattern and texture background image
│   └── music.mp3              # Background instrumental audio
├── css/
│   ├── style.css              # Main styling, typography, and color palette
│   ├── animations.css         # Keyframe animations and transitions
│   └── responsive.css         # Responsive rules for mobile and tablet screens
└── js/
    ├── main.js                # Opening gate logic, music controller, parallax, and navigation
    ├── animations.js          # IntersectionObserver scroll reveal & WhatsApp RSVP submission
    └── countdown.js           # Live countdown timer to 26 December 2026, 12:30 PM
```

---

## 🚀 How to Run Locally

### Option 1: Open Directly in Browser
Double-click `index.html` or open it with Google Chrome, Safari, or Microsoft Edge.

### Option 2: Run with Python HTTP Server
Open your terminal in this directory and run:
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

---

## ✨ Features

- **Tap-to-Enter Opening Gate**: Elegant gate screen with Arabic calligraphy (*Bismillah*) and envelope icon prompt that transitions smoothly into the invitation.
- **Background Music**: Autoplays upon opening the invitation with a floating music toggle button in the bottom corner.
- **Live Countdown Timer**: Automatically counts down to Saturday, 26 December 2026 at 12:30 PM.
- **Side Navigation & Floating Navigation**: Interactive side dot navigation tracking current view section with `A & R` shimmer monogram.
- **Interactive Wedding Events**: Event cards for Nikah and Lunch with direct Google Maps navigation buttons to MS Community Hall, Mulbagal.
- **Family & Hosts Cards**: Cards for Groom's family, Bride's family, Invitation Hosts (Muthvali Abdul Rawoof Saheb & Family), and Special Invitation (KGN Group).
- **Love Story Timeline**: Animated milestone cards showing the journey.
- **WhatsApp RSVP Integration**: Allows guests to specify their name, number of guests, and dua/message, formatting and sending directly via WhatsApp.
