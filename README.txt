VoiceCall Offline — fixed V4

This build fixes a JavaScript syntax error that prevented the previous V3 build
from running. The service-worker cache name was also changed so the browser
will fetch the corrected files.

Upload/replace:
- index.html
- manifest.json
- service-worker.js

After deployment, open the HTTPS site once and refresh. If the installed PWA
still shows the old broken version, clear the site's data/cache and reinstall it.

The app uses the browser's SpeechRecognition engine. Accent-tolerant matching
and local pronunciation aliases are included, but the browser itself does not
provide a true offline Ijaw acoustic model.
