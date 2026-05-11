# TD Bank Mobile Automation — IOS

Generated: 2026-05-11T01:21:07.615Z
Platform: ios
Suites: 3
Total Scenarios: 75

## Suites
- **Transfers, Payments & Mobile Deposit** (`transfers-ios.spec.js`) — 25 scenarios
- **Account Management & Dashboard** (`accounts-ios.spec.js`) — 25 scenarios
- **Authentication & Security** (`auth-ios.spec.js`) — 25 scenarios

## Setup
```bash
npm install webdriverio @wdio/appium-service appium
npx appium driver install xcuitest
npx wdio run wdio.conf.js
```

## Requirements
- Appium 2.x server running on localhost:4723
- iOS device or simulator with TD Bank app installed