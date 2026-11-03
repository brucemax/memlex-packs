---
title: Memlex privacy policy
permalink: /privacy-policy.html
---

# Memlex privacy policy

Effective: 3 November 2026

Memlex is a vocabulary app for Android and iPhone. This policy says what happens to your data when you use it.

## The short version

- No accounts, no sign-in.
- No analytics, no ads, no tracking, no crash reporting.
- Your words, lists, pictures you chose and your learning progress are stored only on your device.
- The developer does not receive or sell any personal data.

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

Nothing else is sent: no identifiers, no usage statistics, no contents of your lists.

## Children

The app collects no personal data from anyone, children included.

## Changes

If the app starts sending any other data, this policy will be updated first, with a new effective date.

## Contact

Questions about privacy: [maximpipkin@gmail.com](mailto:maximpipkin@gmail.com)
