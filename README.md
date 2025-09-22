# 🚀 Marodim - Discord Webhook Spammer

> ⚠️ **DISCLAIMER**: This tool is for educational purposes only. Use responsibly and in compliance with Discord’s Terms of Service. Unauthorized or abusive use may result in account or webhook termination.

---

## 📌 Overview

**Marodim** is a sleek, browser-based Discord Webhook Spammer tool built with pure HTML, CSS, and JavaScript. It allows users to send repeated messages via Discord webhooks with customizable delays, usernames, avatars, and real-time analytics. Includes features like message history, webhook deletion, rate-limit handling, and progress tracking.

Perfect for stress-testing, bot development, or automation — but **always use ethically**.

---

## ✨ Features

- 🔥 **Glowing Cyberpunk UI** with animated particles & smooth transitions
- 📊 **Real-Time Stats**: Messages sent, success rate, elapsed time
- ⏱️ **Customizable Delay** between messages (in milliseconds)
- 🧪 **Test Message** button to verify webhook before mass sending
- 🗑️ **Delete Webhook** functionality
- 📜 **Message History** log with status (success/error/rate-limited)
- 🎨 **Custom Username & Avatar URL** support
- 📈 **Progress Bar** animation for visual feedback
- ⌨️ **Keyboard Shortcuts**:
  - `Ctrl + Enter` → Start sending
  - `Esc` → Stop sending or close modals
- 🌐 **Responsive Design** — works on mobile & desktop

---

## 🛠️ How to Use

1. **Open `index.html`** in any modern browser (Chrome, Firefox, Edge, etc.)
2. Fill in the required fields:
   - **Webhook URL** *(required)*
   - **Message Content** *(required)*
   - Optional: Username, Avatar URL, Delay (default: 1000ms)
3. Click **“🚀 Start Sending”** to begin spamming
4. Use **“⏹️ Stop”** to halt the process
5. Use **“🧪 Test Message”** to send a single test message
6. Access **“🗑️ Delete Webhook”**, **“ℹ️ About”**, or **“📊 Message History”** via footer links

---

## ⚙️ Technical Details

- **No Backend Required** — runs 100% client-side
- **Validates Webhook URLs** using regex: `^https://discord.com/api/webhooks/\d+/[\w-]+$`
- **Handles Rate Limits** (HTTP 429) gracefully
- **Tracks Success/Failure** per message
- **Stores last 100 messages** in history with timestamps
- **Animated Background Particles** for immersive experience
- **CSS Animations & Gradients** for modern cyber aesthetic
