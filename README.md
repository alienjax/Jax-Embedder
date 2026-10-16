# Music Artwork Embedder for macOS

A fast, lightweight, and modern macOS utility designed to extract album cover images from the Apple Music database and embed them directly into your audio files for safekeeping.

![App Preview](https://github.com/YOUR-USERNAME/music-artwork-embedder/raw/main/preview.png) *(Optional: add a screenshot link here if you have one)*

---

## Features
* **Lightning Fast:** Batches AppleScript commands locally to process tracks instantly.
* **Modern & Seamless:** Translucent, borderless window with smooth state animations.
* **Smart Placeholders:** Automatically falls back to custom art if a track has no embedded cover.
* **Audible Feedback:** Plays a custom chime sound upon completion.

---

## 📥 Download & Installation

1. Go to the [Releases](https://github.com/YOUR-USERNAME/music-artwork-embedder/releases) page.
2. Download the latest **`Music-Artwork-Embedder.zip`** file.
3. Unzip the file and drag **Music Artwork Embedder.app** into your **Applications** folder.

### ⚠️ First-Time Launch (Gatekeeper Bypass)
Because this app is distributed directly without an Apple Developer certificate, macOS will block it on the first launch. 

**How to open it:**
1. **Right-click** (or hold `Control` and click) on the app icon.
2. Click **Open** from the menu.
3. Click **Open** again on the security warning prompt. 
*(You only need to do this once!)*




--------------------------------------------------------------------
  MUSIC ARTWORK EMBEDDER — FIRST-TIME LAUNCH INSTRUCTIONS
--------------------------------------------------------------------

Because this application is distributed directly without an Apple Developer
License, macOS Gatekeeper may present a security prompt such as "Developer
cannot be verified" or "App is damaged and can't be opened." 

Follow one of the easy methods below to launch the app:

--------------------------------------------------------------------
METHOD 1: THE QUICK RIGHT-CLICK WORKAROUND (RECOMMENDED)
--------------------------------------------------------------------
1. Open your Downloads or Applications folder in Finder.
2. Right-click (or hold 'Control' and click) on "Music Artwork Embedder.app".
3. Select "Open" from the context menu.
4. When the macOS security prompt appears, click "Open" again.

* Note: You only need to do this the very first time! After that, 
  you can open the app normally by double-clicking it.


--------------------------------------------------------------------
METHOD 2: IF MACOS SAYS "APP IS DAMAGED AND CAN'T BE OPENED"
--------------------------------------------------------------------
If macOS tagged the file with a download "quarantine" flag, you can clear 
it in seconds using Terminal:

1. Open Terminal (Press Command + Space, type "Terminal", hit Enter).
2. Type the following command followed by a space:

   xattr -d com.apple.quarantine 

3. Drag "Music Artwork Embedder.app" from Finder directly into the 
   Terminal window to auto-fill its exact path.

   (It will look something like this:
    xattr -d com.apple.quarantine /Applications/Music\ Artwork\ Embedder.app)

4. Press Enter and open the app!


--------------------------------------------------------------------
METHOD 3: GRANTING APPLE MUSIC PERMISSIONS
--------------------------------------------------------------------
When you click "Embed Artwork" for the first time:

1. macOS will show a prompt asking for permission to control "Music.app".
2. Click "OK" or "Allow".

* If you accidentally click "Don't Allow":
  Go to System Settings -> Privacy & Security -> Automation 
  and turn ON the toggle under "Music Artwork Embedder".
