# 🪐 Bug Bounty Checklist 🛸

A comprehensive, interactive checklist for web application penetration testers and bug bounty hunters. Track your testing methodology and never miss critical security tests again.

![GitHub](https://img.shields.io/badge/Status-Active-brightgreen)
![GitHub](https://img.shields.io/badge/Platform-Web-blue)
![GitHub](https://img.shields.io/badge/Firebase-Enabled-orange)

## 🚀 Features

- ✅ **Interactive Checklist** - Mark tests as complete with real-time progress tracking
- 🔐 **Firebase Integration** - Save your progress automatically (requires sign-in)
- 🎯 **Right-Click Context Menu** - Quickly add categories, subsections, and items
- 📊 **Progress Analytics** - Visual progress bar and completion statistics
- 🔄 **Export/Import** - Backup your checklist or share with others
- 📱 **Responsive Design** - Works perfectly on desktop and mobile
- 🌙 **Dark Theme** - Easy on the eyes during long testing sessions

## 🛠️ Built With

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: Firebase (Firestore, Authentication)
- **Icons**: Custom SVG + Emojis
- **Hosting**: GitHub Pages

### Run Locally
```bash
# Clone the repository
git clone https://github.com/your-username/bug-bounty-checklist.git

# Open the HTML file
cd bug-bounty-checklist
open index.html

```
### 🔥 Firebase Setup

### 1. 🚀 Create Project
- 🌐 Go to [Firebase Console](https://console.firebase.google.com)
- 📁 Create project **"bug-bounty-checklist"**
- 📊 Disable **Google Analytics**

### 2. ⚙️ Enable Services
- 🔐 **Authentication** → **Google provider** → Add domains:
- 🖥️ `localhost`
- 🌍 `your-username.github.io`
- 💾 **Firestore Database** → Start in **test mode**

### 3. 🔧 Update Config
Replace in `index.html`:

```javascript
const firebaseConfig = {
  apiKey: "your-api-key",
  authDomain: "your-project.firebaseapp.com",
  projectId: "your-project-id",
  storageBucket: "your-project.appspot.com",
  messagingSenderId: "123456789",
  appId: "your-app-id"
};
```
### Usage

- ▶️ Click arrows to expand/collapse
- ✅ Check boxes to mark complete
- 🖱️ Right-click for context menu:
- 📁 Add categories/items
- 🔄 Expand/collapse sections
- 🗑️ Delete nodes



