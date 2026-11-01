# Privacy Policy

Last updated: August 2026

## Overview

SnapMeta ("the app") is a desktop metadata studio for microstock content. It
helps creators generate titles, descriptions, and keywords, and write them
directly into image and vector files.

## What we collect

SnapMeta is a **local desktop application**. We do not operate servers, do not
collect analytics, and do not sell or share personal data.

The only data that leaves your computer is the data you explicitly choose to
send to an AI provider or to the license server:

- **Images / files you process**: when you generate metadata, the selected
  file (or a downscaled preview of it) is uploaded to the AI provider you
  configured (e.g. OpenAI, Google Gemini, Groq, OpenRouter, or a custom
  endpoint) so the AI can describe its content.
- **Prompt text and chat history**: topics, keywords, messages, and settings you
  type are sent to the same AI provider as part of the request. Saved chat
  conversations are stored only on your device; only the messages included in
  the current request are sent to the provider.
- **API keys**: your AI provider API key is sent only in the Authorization
  header of requests to that provider. It is stored locally on your device
  and is never transmitted anywhere else.
- **License key**: when you activate or re-validate a purchase, the license
  key and a device name are sent to Lemon Squeezy (lemonsqueezy.com) to verify
  the license. Only the result and the license metadata are stored locally.

## Where data is stored

- Your AI provider configuration (base URL, model, API key, upload
  preferences), saved chat conversations, theme, rules, and cached license are
  stored locally on your device in the app's preferences file
  (`%APPDATA%\SnapMeta\SnapMeta\shared_preferences.json` on Windows).
- These files live in your Windows user profile. They are **not** included in
  SnapMeta's installer, build output, or updates.
- Your license key, activation instance, and the last validation result are
  stored locally so the app can work offline.
- Generated metadata is written only into the files you choose.

## Licensing and AI features

Metadata generation is free and never requires a license. Ideas and Chat do:
they sit behind a lock overlay while no license is active. If a license is
deactivated, refunded, or disabled, those pages lock again and cannot use a
previously saved API key. The key remains on your device so you can resume after
reactivating, but it is hidden and unusable while the license is inactive.

## Third parties

Processing is performed by the AI provider you configure. Their handling of
your data is governed by their own privacy policies. By using these features
you consent to transmitting your content to the provider you selected.

License activation and validation are handled by Lemon Squeezy. Their
handling of the license key and device name is governed by the Lemon Squeezy
privacy policy.

## Update checks

The EXE build can check GitHub Releases for a newer version. That request goes
to `api.github.com` and carries no account or usage data — only the standard
network metadata (IP address and HTTP headers). SnapMeta uses the response to
compare version numbers and caches the result locally for 24 hours. Microsoft
Store builds do not contact GitHub; the Store delivers their updates.

SnapMeta bundles Ghostscript (AGPL-3.0) for converting EPS files; see
`THIRD_PARTY_NOTICES.md` for details. Ghostscript does not transmit data over
the network.

## Your choices

- You can revoke network access to the AI providers at any time by clearing
  your API keys in the app's Settings page.
- You can deactivate this device in Settings to release the license
  activation, and delete all locally stored configuration by uninstalling the
  app or clearing its local data.

## Contact

Questions about this policy: blackzedo@gmail.com
