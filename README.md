# Lexicon (Flashcard)

A minimalist, responsive iOS dashboard app that serves as a random word and quote generator. It preserves your exact raw CSV strings, dynamically evaluating whether to render them as a structured vocabulary definition card (if a colon `:` is present) or a stylized thought quote layout.

---

## Installation via iOS Shortcuts App

Using the built-in iOS Shortcuts app is the cleanest way to open your local HTML file as if it were a native app. This method allows iOS to automate the launch process and display the document directly inside a native window.

### Step 1: Transfer the HTML File to Your iPhone
1. On your Mac or primary device, locate the updated `.html` file.
2. Use **AirDrop** to send the file directly to your iPhone.
3. On your iPhone, accept the incoming file and choose to save it in your local storage directory (e.g., in the **Files** app under "On My iPhone" or a dedicated iCloud folder).

### Step 2: Create the Shortcut
1. Launch the built-in **Shortcuts** app on your iPhone.
2. Tap the **+ (plus sign)** in the top-right corner to create a new shortcut.
3. Tap **Add Action**, search for **File**, and select the **"File"** action block.
4. Tap the blue **"File"** variable placeholder inside the action box and browse to select your transferred `.html` file from your storage folder.
5. Tap the search bar at the bottom, search for a second action called **Show Web Page** (or *Show Web View* depending on your iOS version), and add it directly right below the first action. It will automatically link itself to read: **"Show File in Web Page"**.

### Step 3: Add to Home Screen
1. Tap the downward arrow at the very top next to the shortcut's default name.
2. Choose **Add to Home Screen** from the dropdown menu.
3. Give it your preferred app name (e.g., *Lexicon*, *The Split Card*, or *Verbiage*).
4. *(Optional)* Tap the icon placeholder square next to the name to select a custom color, glyph, or home screen photo.
5. Tap **Add** in the top right corner.

---

## How It Works
Tapping the icon on your Home Screen bypasses the manual file browser completely and executes your HTML document instantly. Because the user-interface buttons are built as non-semantic `<div>` elements combined with inline JavaScript event handlers, you can tap **>** to cycle through your vocabulary seamlessly.