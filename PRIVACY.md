# iTrackPad Privacy Policy

Last updated: 2026-04-07

한국어: [PRIVACY.ko.md](./PRIVACY.ko.md)

`iTrackPad` is designed to work primarily over your local network between your iPhone and your Mac.

## What the app processes

- Device identity needed for trusted pairing
- Touch, gesture, and pointer intent data that you generate while using the trackpad surface
- Local diagnostics such as connection state, packet counts, and latency estimates
- App settings such as appearance, pointer tuning, scroll tuning, and trusted device preferences

## How data is used

- To discover nearby Macs running the Mac build of `iTrackPad`
- To establish an encrypted local session between your iPhone and your Mac
- To remember trusted devices that you explicitly pair
- To apply your settings and improve reliability during reconnects and troubleshooting

## What the app does not do

- It does not require an account
- It does not sell your data
- It does not use advertising SDKs
- It does not send your touch or gesture input to our servers as part of the core remote trackpad feature

## Local network and encryption

The app uses Bonjour and local network transport to discover and connect to nearby Macs. Touch and gesture payloads are intended to be protected in transit using the app's encrypted session design rather than being sent as raw plaintext.

## Storage on your devices

The app may store the following on your device:

- Trusted device records
- Pairing state needed for reconnect flows
- App preferences and tuning settings
- Local diagnostic summaries

Cryptographic identity material is stored locally using Apple platform storage mechanisms.

## Diagnostics

Debug-oriented diagnostics and verbose logging are intended for development and troubleshooting. If enabled in development builds, they may include operational details such as connection state, event counts, or timing data. These diagnostics are not intended as advertising or profiling systems.

## Third-party services

This project currently does not require a third-party backend service for its core local-control flow.

## Your choices

- You can revoke trusted devices from within the app
- You can force fresh pairing
- You can disable optional touch feedback and diagnostics toggles
- You can remove the app from your devices at any time

## Contact

For privacy questions or requests, contact:

- `shteosis@gmail.com`
