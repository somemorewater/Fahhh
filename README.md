# Fahhhh PWA

A Progressive Web App that plays a "fahhhh" sound whenever you click anywhere on the screen. Works offline after installation!

## Features

- Click anywhere to play the "fahhhh" sound
- Installable as a Progressive Web App
- Works completely offline after installation
- Shows online/offline status
- No external dependencies

## How to Install in Chrome

### Desktop (Windows, Mac, Linux):

1. **Open the website** in Google Chrome
2. Look for the **install icon** (➕ or ⬇️) in the address bar on the right side
3. Click the install icon
4. Click **"Install"** in the popup dialog
5. The app will open in its own window and be added to your applications

**Alternative method:**
1. Click the **three dots menu** (⋮) in the top-right corner
2. Select **"Install Fahhhh Sound Player..."** or **"Save and Share" → "Install app"**
3. Click **"Install"** in the dialog

### Mobile (Android):

1. **Open the website** in Chrome on your Android device
2. Tap the **three dots menu** (⋮) in the top-right corner
3. Select **"Install app"** or **"Add to Home screen"**
4. Tap **"Install"** in the dialog
5. The app icon will appear on your home screen

### iOS (iPhone/iPad):

1. **Open the website** in Safari (not Chrome, as iOS doesn't support PWA installation in Chrome)
2. Tap the **Share button** (square with arrow pointing up) at the bottom
3. Scroll down and tap **"Add to Home Screen"**
4. Name the app and tap **"Add"**
5. The app icon will appear on your home screen

## How to Use

1. **Install the app** using the instructions above
2. **Open the installed app** (it works offline!)
3. **Click or tap anywhere** on the screen to play the "fahhhh" sound
4. Enjoy the visual animations and ripple effects!

## Technical Details

- **Service Worker** enables offline functionality
- **Manifest.json** makes it installable as a PWA
- All code is self-contained in HTML, CSS, and JavaScript

## Files

- `index.html` - Main application file (HTML, CSS, JavaScript)
- `manifest.json` - PWA configuration
- `sw.js` - Service Worker for offline caching

## Offline Capability

Once installed, this app works completely offline because:
- All files are cached by the Service Worker
- Audio is generated programmatically (no audio files to download)
- No external dependencies or API calls

## Browser Support

- Chrome (Desktop & Android) - Full support
- Edge - Full support
- Safari (iOS) - Install via "Add to Home Screen"
- Firefox - Works but limited PWA support
- Opera - Full support

## Development

To test locally:
1. Serve the files using a local web server (required for Service Workers)
2. Example: `python -m http.server 8000`
3. Open `http://localhost:8000` in Chrome
4. The install prompt should appear automatically

Note: Service Workers require HTTPS in production, but work on `localhost` for development.


Enjoy your offline fahhhhh!
