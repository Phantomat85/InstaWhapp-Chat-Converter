# Chat Converter GUI (Instagram + WhatsApp)

📥 A powerful and user-friendly Python GUI tool to convert and visualize chat backups from **Instagram** and **WhatsApp**. Supports `.json`, `.html`, and `.txt` files — with customizable output to `.txt` and `.html`, rich formatting, and media handling.

## ✨ Key Features

- ✅ Full-featured **graphical interface** with easy file selection
- 🔍 **Scan entire folders or ZIP archives** for supported files
- 🧠 **Advanced duplicate detection**, even across IG/W labels
- 🎨 **Color-coded preview**:  
  - 💜 Instagram (IG)  
  - 💚 WhatsApp (W)
- ✏️ **Live editable preview** with **search bar**
- 📷 **Media support**: show images, audio, and video inline
- 🛠 **Symbol customization** (e.g., use 🟣 or 🟢 instead of (IG)/(W))
- 🔧 **Flexible placement of origin markers**:  
  - After the colon  
  - After the sender’s name  
  - Or hidden
- 💾 **Preset system**: save and reuse favorite configurations
- 🌐 **HTML export** with modern design, participant filters, and media embedding
- 📊 **Conversation selector** for multi-thread Instagram exports
- 🔜 **Coming soon**: PDF export, print module, and Markdown conversion

## 📂 Supported Input Formats

- `message_1.json` → Instagram chat backups (JSON)
- `message_1.html` → Instagram chat backups (HTML)
- `.txt` → WhatsApp plain text exports

## 🧰 Requirements

- Python 3.8 or higher
- Dependencies:
  - `beautifulsoup4`
  - `tkinter` (built-in with Python)

Install beautifulsoup4 with:
```bash
pip install beautifulsoup4
