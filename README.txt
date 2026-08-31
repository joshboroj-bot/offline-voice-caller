# Offline Voice Caller PWA

Files:
- index.html — main app
- manifest.json — Android PWA installation metadata
- service-worker.js — offline cache

IMPORTANT:
The service worker and browser microphone APIs require the app to be opened from a secure origin (HTTPS) for normal browser/PWA operation. Install the PWA once while online, grant microphone permission, and then the cached app can run offline.

The app's phone calls still use the Android phone/cellular network and therefore use airtime.
