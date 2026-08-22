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
send to an AI provider:

- **Images / files you process**: when you generate metadata, the selected
  file (or a downscaled preview of it) is uploaded to the AI provider you
  configured (e.g. OpenAI, Google Gemini, Groq, OpenRouter, or a custom
  endpoint) so the AI can describe its content.
- **Prompt text**: topics, keywords, and settings you type are sent to the
  same AI provider as part of the request.
- **API keys**: your AI provider API key is sent only in the Authorization
  header of requests to that provider. It is stored locally on your device
  and is never transmitted anywhere else.

## Where data is stored

- Your AI provider configuration (base URL, model, API key, upload
  preferences) is stored locally on your device via the app's local
  preferences storage.
- Generated metadata is written only into the files you choose.

## Third parties

Processing is performed by the AI provider you configure. Their handling of
your data is governed by their own privacy policies. By using these features
you consent to transmitting your content to the provider you selected.

SnapMeta bundles Ghostscript (AGPL-3.0) for converting EPS files; see
`THIRD_PARTY_NOTICES.md` for details. Ghostscript does not transmit data over
the network.

## Your choices

- You can revoke network access to the AI providers at any time by clearing
  your API keys in the app's API Key settings.
- You can delete all locally stored configuration by uninstalling the app or
  clearing its local data.

## Contact

Questions about this policy: blackzedo@gmail.com
