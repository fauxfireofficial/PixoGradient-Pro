# 🎨 Pixo AI - Advanced Image Editor & AI Generator
**Developed by Faux-Fire Official**

Pixo AI is a high-performance web application designed for seamless photo editing and AI image generation. Built with a "Mobile-First" approach, it is fully optimized to be converted into a native Android/iOS app using **Cordova** or **Capacitor**.

---

## 🚀 Key Features

### 1. ⚡ AI Image Generation (Powered by Pollinations.ai)
* **Text-to-Image:** Transform prompts into high-quality visuals.
* **Aspect Ratios:** Supports 1:1 (Square), 9:16 (Portrait), and 16:9 (Landscape).
* **Smart UI:** Real-time generation feedback with a dedicated AI tab.

### 2. 🪄 Gradient Studio & Photo Editor
* **15+ Pro Presets:** 'Sunset Glow', 'Ocean Breeze', 'Violet Sunrise', 'Fire & Ice', and more.
* **Precision Controls:** * Adjust Opacity, Brightness, and Contrast.
    * Advanced filters: Saturation, Vibrance, Temperature, and Sharpness.
* **Before/After Toggle:** Compare edits instantly using the interactive slider.

### 3. 📂 Local Gallery & Management
* **Auto-Save:** Generated and edited images are stored in a clean, grid-based local gallery.
* **File Actions:** One-click Download and Delete functionality.

### 4. 🔗 Social & Feedback
* **Smart Sharing:** Integrated sharing via WhatsApp, Telegram, and SMS.
* **EmailJS Integration:** Built-in feedback system for direct user-to-developer communication.

### 5. Credits/Usage Limit**
Chunkay aapne `index.html` mein **DAILY_LIMIT** rakha hua hai, toh README mein iska zikr karna acha lagta hai taake user ko pata ho:
```markdown
## 🪙 Credit System
To ensure fair usage of the Pollinations AI API, the app includes a local credit system:
- **Daily Limit:** 8 AI Generations per day.
- **Reset:** Credits reset every 24 hours automatically.

---

## 🛠️ Technical Stack
* **Frontend:** HTML5, CSS3 (Custom Dark Theme), JavaScript (ES6+).
* **API:** Pollinations.ai (AI Image Generation).
* **Communication:** EmailJS (Feedback).
* **Native Bridge:** Cordova / Capacitor ready.

---

## 📱 Mobile Conversion (Cordova Guide)

### 1. Initialize Project
```bash
# Create project
cordova create PixoAI com.fauxfire.pixo PixoAI
cd PixoAI

# Add Android Platform
cordova platform add android

## 📄 License
This project is for portfolio purposes. Please contact **Faux-Fire Official** for commercial usage permissions.
