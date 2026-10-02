# Privacy

_Last updated: October 2, 2026_

Structa is a document scanning and document-understanding app. Because documents can contain personal or confidential information, privacy should be considered before using any feature that sends data over the network.

## Document scanning and OCR

Structa processes scans and extracts text so documents can be viewed, organized and used inside the app.

The current app is designed to perform document and OCR work locally where the selected feature allows it. Some Android or platform components used for scanning may be provided by device services.

## Ask Structa

**Ask Structa is an online feature.**

When you ask a question about a document, the document context needed to answer that request is sent over the internet to Structa's backend and the configured AI service. This is necessary to generate the answer.

Do not use Ask Structa with information you are not comfortable sending to a remote service.

## Account features

If you choose to use account features, the information necessary for authentication is processed by the authentication service configured for Structa. The exact service configuration may change as the app evolves.

## Permissions

Depending on the feature you use, Structa may request access to:

- **Camera** — to scan physical documents.
- **Photos / files / documents** — to import, save or share documents when you choose to do so.
- **Internet** — for Ask Structa, account features and other network-backed functionality.

Structa should only request permissions when they are needed by a feature.

## Public GitHub issues

This repository is public. **Never upload private documents, scans, account credentials, API keys, tokens, personal identification or other sensitive data to an Issue.**

When reporting a bug, redact screenshots and logs before posting them.

## Data retention and third parties

This public repository does not currently make a blanket promise about server-side retention periods for every network-backed service. Service providers and backend behavior may change between builds.

For highly sensitive or regulated documents, review the behavior of the specific Structa version you are using before submitting document content to online features.

## Changes

This notice may be updated as Structa's features, infrastructure or distribution model change.

For security-sensitive reports, follow [SECURITY.md](SECURITY.md).
