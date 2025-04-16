
---

```markdown
# 🔐 SecurePass – Chrome Extension for Strong Password Generation

**SecurePass** is a lightweight and user-friendly Chrome extension that helps you generate strong, secure, and customizable passwords on the fly. Designed with simplicity and privacy in mind, it ensures your credentials remain safe without storing any data.

## 🚀 Features

- Generate secure passwords instantly
- Customize length and character types:
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Special symbols
- Copy generated password to clipboard with one click
- Responsive and intuitive UI
- Fully compatible with modern browsers (Manifest v3)

## 🖥️ Preview

![SecurePass UI](./SecurePass/icon48.png)

## 📦 Installation

1. **Clone or Download this repository**:
   ```bash
   git clone https://github.com/yourusername/SecurePass.git
   ```

2. **Open Chrome** and go to:
   ```
   chrome://extensions/
   ```

3. Enable **Developer Mode** (toggle on top-right).

4. Click **"Load unpacked"** and select the `SecurePass` folder.

5. The extension will now appear in your Chrome toolbar.

## 🛠️ Tech Stack

- **Frontend**: HTML, SCSS, JavaScript
- **Extension Platform**: Chrome Extensions API (Manifest v3)

## 📁 File Structure

```
SecurePass/
├── icon48.png                 # Extension icon
├── manifest.json              # Chrome extension config
├── popup.html                 # Extension popup UI
├── popup.js                   # Logic for password generation
├── popupStyles/
│   ├── popup.css              # Compiled CSS
│   ├── popup.css.map
│   └── popup.scss             # SCSS source styles
```

## ✨ Manifest Permissions

This extension does **not** require any special permissions. It runs entirely in the browser and does not store or send any data.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---