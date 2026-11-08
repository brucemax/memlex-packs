---
title: Memlex privacy policy
permalink: /privacy-policy.html
---

# Memlex privacy policy

Effective: 8 November 2026

Memlex is a vocabulary app for Android and iPhone. This policy says what happens to your data when you use it.

## The short version

- No accounts, no sign-in, no ads, no tracking across apps.
- Your words, lists, pictures you chose and your learning progress are stored only on your device.
- The app sends anonymous usage statistics and crash reports to Google Firebase, never your words. You can turn this
  off in Settings.
- The developer does not sell any data.

## What stays on your device

Everything you create in the app: words and their translations, lists, examples, chosen pictures, review history,
streaks, achievements and settings. It is not uploaded anywhere. Deleting the app deletes it. Exporting a list to a
file is something you do yourself, and the file goes where you send it.

## What the phone's own services do

The app uses features built into your phone. They are provided by Apple (iPhone) or Google (Android) under their own
privacy policies, and the developer receives nothing from them:

- **Speech recognition** (saying a word to add it). The app asks for on-device recognition where the phone supports
  it; otherwise the phone's recognition service may send the audio to Apple or Google to turn it into text.
- **Speech synthesis** (hearing a word). Done by the phone's voices.
- **Text recognition** (taking a photo of a word list). Done on the device; the app reads the words and does not keep
  the photo.
- **Machine translation** (when the dictionary has no translation). Done on the device by Apple Translation or
  Google ML Kit; the translation models are downloaded once from Apple or Google.
- **Reminders.** Local notifications scheduled on the device.

## What leaves your device

- **Language packs** (dictionaries) are downloaded from GitHub (github.com). Like any website, GitHub sees your
  device's IP address when it serves the files. No information about you is sent with the download.
- **Picture search.** When you search for a picture for a word, the app sends the word (and, if needed, its
  translation) and the languages of your pair to the app's picture server (Cloudflare Workers). The server asks
  Pixabay for pictures; Pixabay sees the search words but not your IP address. The server keeps search results for a
  day and copies of the pictures it delivered, to answer the next request faster; it does not store who searched.
  Cloudflare sees your IP address to deliver the response and to limit the number of requests per address.

- **Usage statistics and crash reports**, described in the next section.

Nothing else is sent: no contents of your lists.

## Usage statistics and crash reports

To see whether the app works and where it needs improving, the app uses two Google services: Google Analytics for
Firebase (usage statistics) and Firebase Crashlytics (crash reports).

**What is sent:**

- Events about how the app is used: onboarding steps reached and whether onboarding was finished, a word saved and
  whether it was typed, spoken or taken from a photo and saved with a picture, a learning session finished with its
  mode and number of cards, a starter list added or words imported with their number, a language pack downloaded
  with its languages and whether it worked.
- The app's edition, its interface language and the language you translate into.
- When the app crashes: the technical report of the crash (where in the app's code it happened), the app version,
  the device model and the system version.
- Random identifiers created by Firebase for this installation of the app, used to count users and group reports.
  They are not linked to your name, email or any account.
- Like any internet service, Google sees your device's IP address when receiving the data.

**What is never sent:** your words, translations, examples, list names, pictures, photos, recordings, search queries,
file names or anything else you type, say or photograph; the advertising identifier of your device. The data is not
used to track you across other apps or websites and is not used for advertising.

**How long it is kept:** crash reports are kept by Firebase for 90 days; usage events are kept for 2 months, after
which only aggregated, anonymous reports remain.

**How to turn it off:** Settings → "Share usage statistics and crash reports". When it is off, the app sends neither
usage statistics nor crash reports. It is on by default.

Google processes this data under its own terms and privacy policy (firebase.google.com/support/privacy).

## Children

The app asks no one for personal data, children included. The anonymous usage statistics and crash reports
described above are the same for everyone and can be turned off in Settings.

## Changes

If the app starts sending any other data, this policy will be updated first, with a new effective date.

## Contact

Questions about privacy: [maximpipkin@gmail.com](mailto:maximpipkin@gmail.com)
