# SQLite Contact Manager - Android App

A simple Android contact management app with SQLite database demonstrating CRUD operations.

## 🚀 Quick Setup Guide

### Prerequisites
- Android Studio installed
- JDK installed
- Git installed

### Setup Steps

#### 1. Navigate to AndroidStudioProjects Folder

```bash
cd ~/AndroidStudioProjects
```

For Windows:
```bash
cd C:\Users\YourUsername\AndroidStudioProjects
```

#### 2. Clone the Project

```bash
git clone <repository-url>
cd sqlite
```

#### 3. Open in Android Studio

1. Open Android Studio
2. Click **File → Open**
3. Navigate to `AndroidStudioProjects/sqlite`
4. Click **OK**
5. Wait for Gradle sync to complete

#### 4. Run the App

1. Click the green **Run** button (▶️) or press **Shift+F10**
2. Select your emulator or connected device
3. Wait for the app to install and launch

That's it! 🎉

## 📱 Using the App

1. **Add Contact:** Click the green **+** button at bottom-right
2. **View Contact:** Tap on any contact name
3. **Edit Contact:** Open contact → Menu (⋮) → Edit Contact
4. **Delete Contact:** Open contact → Menu (⋮) → Delete Contact

## 🔧 Troubleshooting

**Gradle sync failed?**
- Check internet connection
- File → Sync Project with Gradle Files

**App not running?**
- Build → Clean Project
- Build → Rebuild Project

**Need an emulator?**
- Tools → Device Manager → Create Device

## 📁 Project Structure

```
sqlite/
├── app/src/main/java/com/example/sqlite/
│   ├── MainActivity.java       # Main screen with contact list
│   ├── DisplayContact.java     # Add/Edit/View contact screen
│   └── DBHelper.java            # Database operations
└── app/src/main/res/
    ├── layout/                  # UI layouts
    └── menu/                    # Menu items
```

## 📝 Features

- ✅ Add, view, edit, delete contacts
- ✅ SQLite database for storage
- ✅ Material Design UI
- ✅ Floating Action Button

## 🎓 Course Info

**Course:** MIS6120 - Mobile Computing  
**Institution:** USIU-Africa

---

