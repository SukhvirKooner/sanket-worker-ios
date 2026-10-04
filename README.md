# SANKET Worker (iOS)

Worker-facing iOS app for SANKET — the workforce action layer.

Helps a worker move from current skills to a future role:

Discover → Understand → Transition → Train → Apply → Get placed → Progress

## Requirements

- Xcode 16+ / iOS 17+ SDK
- iPhone simulator (portrait)

## Run

```bash
open SANKET.xcodeproj
```

Select an iPhone simulator and press Run.

If you edit `project.yml`, regenerate with:

```bash
xcodegen generate
```

## Record a walkthrough

With the iPhone simulator booted and the app installed:

```bash
python3 record_walkthrough.py
```

Output: `Walkthrough/SANKET_Walkthrough.mp4`

## Notes

- Front-end only — all data is local mock data in Swift
- English / हिंदी via `SANKET/Resources/Localizable.xcstrings`
- Long-press **SANKET** on Home for presenter controls
