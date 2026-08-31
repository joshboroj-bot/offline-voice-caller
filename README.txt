VoiceCall Offline PWA V3

This version adds:
- Nigerian English speech recognition default (en-NG)
- accent/pronunciation-tolerant contact matching
- local pronunciation learning for each contact
- "teach [contact name]" / "learn [contact name]" commands
- local-only storage of learned pronunciation aliases

Important:
Web Speech Recognition in Android browsers does not expose a true offline Ijaw
acoustic model. The app therefore improves Ijaw-accented English handling at the
contact-matching layer rather than claiming native Ijaw speech recognition.

Install/update the PWA from HTTPS once, then the app shell and local contact data
can work offline. Normal phone calls still use the cellular network/airtime.
