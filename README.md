# Smalendar

**A local-first Android calendar with AI-assisted planning.**

[![Release](https://img.shields.io/badge/release-v0.1.0--beta.1-2f7d62?style=flat-square)](https://github.com/Johnkoder/smalendar-official/releases/tag/v0.1.0-beta.1)
![Platform](https://img.shields.io/badge/platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Status](https://img.shields.io/badge/status-public_beta-d89b32?style=flat-square)

Smalendar combines a practical on-device calendar with an optional AI planning workflow. Write what you need in everyday language, review the proposed event or reminder, make changes if needed, and approve it before anything is saved.

## Download the beta

### [Download Smalendar v0.1.0-beta.1](https://github.com/Johnkoder/smalendar-official/releases/download/v0.1.0-beta.1/Smalendar-v0.1.0-beta.1.apk)

This is an Android beta distributed as a universal APK. It must be installed manually and is not currently available through Google Play.

## What Smalendar can do

| Capability | What it means |
| --- | --- |
| Local-first calendar | Create, view, edit, and delete events and reminders without an account. |
| AI-assisted planning | Turn one natural-language request into an editable calendar draft. |
| Approval before saving | AI proposals remain drafts until you explicitly approve them. |
| Calendar awareness | Ask about saved items without exposing the whole calendar to the AI provider. |
| Availability checks | Check conflicts and find open time using calculations performed on-device. |
| Local notifications | Schedule reminder and optional event alerts, subject to Android permissions. |
| Light and dark themes | Follow the device theme with an accessible, responsive interface. |

Manual calendar features work offline and do not require an AI provider.

## Install on Android

1. Download `Smalendar-v0.1.0-beta.1.apk` from the link above.
2. Open the downloaded APK on your Android device.
3. If Android asks, allow your browser or file manager to install unknown apps.
4. Complete the installation, then open **Smalendar**.
5. Grant notification or exact-alarm access only if you want scheduled alerts.

Future beta updates signed with the same release identity can be installed over the existing app. Because this build is outside Google Play, updates are not automatic.

## Verify the download

For release `v0.1.0-beta.1`:

```text
APK filename:   Smalendar-v0.1.0-beta.1.apk
APK SHA-256:    529165DDC5C0D46C55C9A7CF72A1ABF3F6E7CE08FC26C316F99F5E0A576E34FA
Signer SHA-256: 9F5413151C39559609E76E253FC2825E1AEB6FECDF22E3BDA8EAFCD884E73150
```

The APK is signed with the Smalendar release certificate (`CN=Johnkoder`). Android may display an unfamiliar-app warning because the APK is installed directly rather than through an app store.

## Privacy and AI

- Calendar items and non-secret settings are stored locally on the device.
- Manual calendar use works without AI and without an internet connection.
- AI prompts are sent only to the provider you configure.
- API keys are kept in Android-backed secure storage and are not written to calendar data.
- Read-only calendar results and availability calculations stay on-device.
- When changing a saved item with AI, only that item's user-visible fields may be sent so the provider can prepare a proposed change.
- AI drafts, edits, and deletions require review or confirmation before the local calendar is changed.

This personal beta connects directly to a user-supplied AI provider key. Use a key with appropriate limits and review your provider's privacy and billing policies.

## Beta limitations

Smalendar currently supports Android only. Recurrence, accounts, sync, backup, device-calendar integration, import/export, widgets, voice input, and automatic updates are not included yet. Uninstalling the app may remove its local calendar data.

Expect rough edges in a beta. Please report reproducible problems through [GitHub Issues](https://github.com/Johnkoder/smalendar-official/issues) and include your Android version, device model, and the steps that triggered the issue. Do not include API keys or other secrets.

## Release

- Current beta: [Smalendar v0.1.0-beta.1](https://github.com/Johnkoder/smalendar-official/releases/tag/v0.1.0-beta.1)
- All releases: [GitHub Releases](https://github.com/Johnkoder/smalendar-official/releases)

---

Smalendar is under active development. Beta behavior and data formats may change before a stable release.
