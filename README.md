# Jax Embedder for macOS

A fast, lightweight, and modern macOS utility designed to extract album cover images from the Apple Music database and embed them directly into your audio files for safekeeping. Free version is limited to process eight tracks at a time.









<p align="center">
  <img src="https://github.com/alienjax/Jax-Embedder/blob/main/ss.png" width="1000" alt="App Screenshot">
</p>




---

## Features
* **Lightning Fast:** Batches AppleScript commands locally to process tracks instantly.
* **Modern & Seamless:** Translucent, borderless window with smooth state animations.
* **Smart Placeholders:** Automatically falls back to custom art if a track has no embedded cover.
* **Audible Feedback:** Plays a custom chime sound upon completion.

---

## 📥 Download & Installation

1. Go to the [Releases](https://github.com/alienjax/Jax-Embedder/releases) page.
2. Download the latest **`Jax Embedder.zip`** file.
3. Unzip the file and drag **Jax Embedder.app** into your **Applications** folder.

### ⚠️ First-Time Launch (Gatekeeper Bypass)
Because this app is distributed directly without an Apple Developer certificate, macOS will block it on the first launch. 

If you get the message **Jax Embedder Not Opened**, "Apple could not verify Jax Embedder is free of malware". Please go to Settings, open **Privacy & Security**, and you'll see a message **Jax Embedder was blocked to protect your Mac**. Click on **Open Anyway**. You'll get a prompt for your password, enter your password and your Mac will launch the app.


--------------------------------------------------------------------
  OTHER OPTIONS IF THE METHOD ABOVE DOESN'T WORK
--------------------------------------------------------------------

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

3. Drag "Jax Embedder.app" from Finder directly into the 
   Terminal window to auto-fill its exact path.

   (It will look something like this:
    xattr -d com.apple.quarantine /Applications/Jax\ Embedder.app)

4. Press Enter and open the app!


--------------------------------------------------------------------
IMPORTANT: GRANTING APPLE MUSIC PERMISSIONS
--------------------------------------------------------------------
When you click "Embed Artwork" for the first time:

1. macOS will show a prompt asking for permission to control "Music.app".
2. Click "OK" or "Allow".

* If you accidentally click "Don't Allow":
  Go to System Settings -> Privacy & Security -> Automation 
  and turn ON the toggle under "Jax Embedder".
