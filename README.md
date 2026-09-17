# 📸 wedding-qr-album - Share Wedding Photos Instantly, No App Needed

[![Download Now](https://img.shields.io/badge/Download-wedding--qr--album-2ea44f?style=for-the-badge)](https://github.com/Altatov05/wedding-qr-album)

## 🎯 What Is This?

wedding-qr-album is a free, self-hosted photo sharing tool designed specifically for weddings and events. Your guests simply scan a QR code with their phone camera, and they can instantly upload photos and videos to a shared album. No app to install, no account to create, no monthly fees. Everything runs on your own computer or server.

## ✨ Key Features

- **📱 No App Required** – Guests use their phone's built-in camera to scan the QR code. That's it.
- **🔒 Complete Privacy** – Your photos stay on your own device. No third-party cloud services.
- **🖼️ Automatic Image Processing** – Photos are optimized and resized automatically for fast viewing.
- **🧱 Beautiful Masonry Layout** – Photos display in a modern, Pinterest-style grid that adapts to any screen.
- **🎥 Video Support** – Guests can share both photos and short video clips.
- **💾 SQLite Database** – Simple, reliable storage that requires no separate database setup.
- **⚡ Fast and Lightweight** – Built with modern SvelteKit technology for quick loading even on slower connections.
- **🔧 Easy Self-Hosting** – Runs in Docker or directly on your machine with minimal configuration.

## 🚀 Getting Started

Visit this link to download the application: [https://github.com/Altatov05/wedding-qr-album](https://github.com/Altatov05/wedding-qr-album)

Once you're on the GitHub page, click the green "Code" button and select "Download ZIP". This will download a compressed folder to your computer.

### 📦 Installation on Windows (Step-by-Step)

1. **Extract the ZIP file** – Right-click the downloaded ZIP file and choose "Extract All...". Choose a location like your Desktop or Documents folder.
2. **Open the extracted folder** – You'll see several files and folders inside. Don't worry about what they do – you only need to interact with one file.
3. **Run the setup** – Look for a file named `start.bat` or `run-windows.bat` (depending on the version you downloaded). Double-click it. A black command window will open – this is normal and means the program is starting.
4. **Wait for the "Ready" message** – After a few seconds, you'll see text saying something like "Server running at http://localhost:3000". This means the app is working.
5. **Open your browser** – Go to `http://localhost:3000` in any web browser (Chrome, Edge, Firefox). You'll see the main album page.

### 🖥️ System Requirements (Windows)

- **Operating System:** Windows 10 or Windows 11 (64-bit)
- **RAM:** 4 GB minimum (8 GB recommended)
- **Storage:** 500 MB free space for the app, plus space for your photos
- **Internet:** Not required for local use, but needed if guests access from their phones over Wi-Fi

### 📱 Setting Up for Guest Access

1. **Connect to the same network** – Make sure your computer and your guests' phones are on the same Wi-Fi network.
2. **Find your computer's IP address** – Open Command Prompt (press Windows key, type "cmd", press Enter). Type `ipconfig` and press Enter. Look for "IPv4 Address" – it looks like 192.168.1.5 or similar.
3. **Create the QR code** – In the wedding-qr-album interface, click "Generate QR Code". The app will create a QR code that links to `http://[your-IP-address]:3000`.
4. **Print or display the QR code** – Put it on tables, signs, or share it on a screen at the venue.

## 🛠️ How It Works

1. **Guest scans the QR code** – Their phone opens the album page in the browser.
2. **Guest taps "Upload"** – They select photos or videos from their phone gallery.
3. **Files upload automatically** – The photos appear in the shared album within seconds.
4. **You manage everything** – You can delete unwanted photos, organize them, and download the full collection after the event.

## 🎨 Customization Options

- **Change the album title** – Edit the settings file to rename your album.
- **Add a welcome message** – Personalize the page with a greeting for your guests.
- **Set upload limits** – Control file size and number of uploads per guest.
- **Enable moderation** – Approve photos before they appear publicly (great for privacy).

## 🔒 Privacy and Security

- **Local-first design** – All photos stay on your computer. Nothing is sent to external servers.
- **Password protection** – You can add a simple password to restrict access to the album.
- **Automatic cleanup** – Optionally set photos to auto-delete after 30 days.

## ❓ Frequently Asked Questions

**Q: Do I need to install any software on my computer?**
A: No. The downloaded ZIP contains everything needed. Just extract and run the batch file.

**Q: Can guests upload from iPhones and Android phones?**
A: Yes. Any phone with a camera and web browser works perfectly.

**Q: What if my Wi-Fi doesn't reach everywhere?**
A: You can use a portable router or mobile hotspot, or run the app on a laptop that moves around.

**Q: How many photos can be uploaded?**
A: There's no hard limit. It depends on your computer's storage space.

**Q: Can I use this for other events?**
A: Absolutely! Birthdays, corporate events, family reunions – any gathering where people want to share photos.

## 🆘 Troubleshooting

- **Port already in use** – If you see an error about port 3000, close other programs or change the port in the settings file.
- **Guests can't connect** – Make sure your firewall allows connections on port 3000. Windows may ask for permission – click "Allow".
- **Slow uploads** – Reduce photo quality in settings or ask guests to upload fewer photos at once.
- **Forgot the QR code** – Just regenerate it from the app interface anytime.

## 💡 Tips for Best Results

- **Test before the big day** – Set everything up a week early and try uploading from your own phone.
- **Create backup** – Copy the album folder to a USB drive after the event.
- **Use a dedicated device** – An old laptop or mini PC works great as a dedicated photo station.
- **Print instructions** – Put a small sign next to the QR code explaining how to use it.

## 📄 License

This project is open-source and free to use for personal and commercial events. No hidden costs, no premium tiers – just a reliable tool for sharing memories.

## 🤝 Contributing

Found a bug or want a new feature? Check the GitHub repository for contribution guidelines. Your feedback helps make this tool better for everyone.

## 📞 Support

- **GitHub Issues** – Report problems or ask questions on the repository's Issues page.
- **Community Discussions** – Join the conversation in the Discussions tab.

## 🔗 Quick Links

- **Download Page:** [https://github.com/Altatov05/wedding-qr-album](https://github.com/Altatov05/wedding-qr-album)
- **Source Code:** Available on the same page
- **Documentation:** Included in the ZIP file (README.md)

---

**Start sharing photos effortlessly at your next event. Download wedding-qr-album today and let your guests capture every moment – no apps, no accounts, no hassle.**

Keywords: docker, event-photography, guest-upload, image-processing, masonry, no-signup, photo-gallery, photo-sharing, photo-upload, privacy, qr-code, qrcode, self-hosted, selfhosted, shared-album, sqlite, svelte, sveltekit, typescript, wedding