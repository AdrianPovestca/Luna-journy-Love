# 🌙 Luna - A Private Period Tracker

**Luna** is a beautiful, empathetic, and strictly private period tracking Progressive Web App (PWA). 

I built this app for my partner because we wanted a safe space to track her cycle without worrying about our personal health data being sold, analyzed, or shared with third-party advertisers. Unlike many mainstream apps, Luna is designed with a **privacy-first** approach: your data never leaves your device.

## ✨ Features

*   **Total Privacy:** All cycle data, symptoms, and moods are stored strictly locally on your device using `localStorage`. There are no servers, no tracking, and no accounts required to start tracking.
*   **Empathetic Design:** A soft, calming, and magical UI designed to feel like a caring friend rather than a clinical medical tool. 
*   **Smart Predictions:** The app learns from your cycle to predict your next period, fertile window, and ovulation day.
*   **Custom Line-Art Icons:** Instead of standard emojis, Luna uses a custom-built SVG icon set (`LunaIcons`) designed specifically for this app to keep the aesthetic consistent and soft.
*   **Cycle-Aware Greetings:** The home screen features dynamic, supportive messages that change based on the time of day and your current cycle phase (e.g., offering extra comfort during the luteal/PMS phase).
*   **PWA Ready:** Installable directly to your iPhone or Android home screen via the browser. No App Store or sideloading required.

## 🛠️ Tech Stack

This project was built using:
*   **Frontend:** React + Vite + TypeScript
*   **Styling:** Tailwind CSS (with custom soft-gradient configurations)
*   **Icons:** Custom inline SVG components
*   **Backend/Auth (Optional):** Supabase (configured for authentication, while keeping cycle data local)

## 🚀 How to Run Locally

If you want to run this project on your own machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/luna-journy-love.git
   cd luna-journy-love
