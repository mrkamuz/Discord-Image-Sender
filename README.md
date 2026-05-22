# Discord Image Sender

A sleek and modern web application that allows users to upload and send images directly to a Discord channel using Discord Webhooks.

## ✨ Features

* 📤 Upload multiple images at once
* 🔄 Automatic batch sending system (5 images per batch)
* ⚡ Infinite queue processing support
* 🔒 Secure webhook URL input with show/hide toggle
* 💾 Saves webhook URL locally using LocalStorage
* 🎨 Modern animated UI with interactive background effects
* 📱 Fully responsive design for desktop and mobile
* 🖼️ File size and image count preview
* ✅ Real-time upload status notifications
* 🚀 Fast and lightweight — no backend required

## 🛠️ Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript
* Discord Webhook API

## 📦 How It Works

1. Paste your Discord Webhook URL
2. Select one or multiple image files
3. The app automatically:

   * Splits files into batches of 5
   * Sends them sequentially
   * Continues until all images are uploaded

## 🔐 Privacy

* No server/backend storage
* All uploads go directly from your browser to Discord
* Webhook URL is stored only in your browser's LocalStorage

## 📸 Supported Files

* PNG
* JPG / JPEG
* GIF
* WEBP
* Other image formats supported by Discord

## 🚀 Usage

Simply open the HTML file in your browser and start uploading images to your Discord server instantly.

## ⚠️ Note

Discord has upload size limits depending on your server boost level. Large batches exceeding the limit may fail.

## 🌌 UI Highlights

* Animated gradient background
* Dynamic interactive line effects
* Glassmorphism-inspired interface
* Smooth transitions and hover animations

## 📄 License

Free to use and modify.
