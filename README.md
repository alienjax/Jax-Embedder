# Jax Embedder for macOS

## Features

A fast, lightweight, and modern macOS utility designed to extract album cover images for multiple tracks from the Apple Music database and embed them directly into your audio files for safekeeping. Free version is limited to process eight tracks at a time.

<p align="center">
  <img src="https://github.com/alienjax/Jax-Embedder/blob/main/Screenshot.png" width="1000" alt="App Screenshot">
</p>

---

## Features
* **Lightning Fast:** Batches AppleScript commands locally to process tracks instantly.
* **Batch Download Artwork** "Download to File" option will download all selected files' artwork to a folder. Format can be PNG, or JPEG, and quality can be chosen in settings. 
* **Modern & Seamless:** Modern macOS style Translucent, borderless window with smooth state animations.
* **Smart Placeholders:** Automatically falls back to custom art if a track has no embedded cover.

---

## Download & Installation

1. Go to the [Releases](https://github.com/alienjax/Jax-Embedder/releases) page.
2. Download the latest **`Jax Embedder.zip`** file.
3. Unzip the file and drag **Jax Embedder.app** into your **Applications** folder.

### ⚠️ First-Time Launch (Gatekeeper Bypass)
Because this app is distributed directly without an Apple Developer certificate, macOS will block it on the first launch. 

If you get messages such as **Jax Embedder Not Opened**, "Apple could not verify Jax Embedder is free of malware", "Developer cannot be verified" or "App is damaged and can't be opened." . Go to Settings, open **Privacy & Security**, and you'll see a message **Jax Embedder was blocked to protect your Mac**. Click on **Open Anyway**. You'll get a prompt for your password, enter your password and your Mac will launch the app.


--------------------------------------------------------------------
Other Options If Method Above Doesn't Work
--------------------------------------------------------------------

For earlier macOS versions:
1. **Right-click** on the app icon.
2. Click **Open** from the menu.
3. Click **Open** again on the security warning prompt. 
*(You only need to do this once!)*

--------------------------------------------------------------------
If macOS Says "App Is Damaged And can't Be Opened"
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
IMPORTANT: Granting Apple Music Permissions
--------------------------------------------------------------------
When you click "Embed Artwork" for the first time:

1. macOS will show a prompt asking for permission to control "Music.app".
2. Click "OK" or "Allow".

* If you accidentally click "Don't Allow":
  Go to System Settings -> Privacy & Security -> Automation 
  and turn ON the toggle under "Jax Embedder".

