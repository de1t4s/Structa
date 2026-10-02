<div align="center">

<img src="docs/images/structa-logo.webp" alt="Structa logo" width="150">

# Structa

**Scan. Organize. Done.**  
*Your documents, understood.*

[![Latest Release](https://img.shields.io/github/v/release/de1t4s/Structa?display_name=tag&sort=semver&label=release)](https://github.com/de1t4s/Structa/releases/latest)
![Android](https://img.shields.io/badge/Android-7.0%2B-3DDC84?logo=android&logoColor=white)
![Distribution](https://img.shields.io/badge/distribution-APK-0B7BA8)
![Source](https://img.shields.io/badge/source-private-555)

**[Download the latest APK](https://github.com/de1t4s/Structa/releases/latest)**

</div>

> [!IMPORTANT]
> This is Structa's **official public distribution repository**. The application source code, backend and development/debug files are maintained privately. Official Android builds are published only through [GitHub Releases](https://github.com/de1t4s/Structa/releases).

## What is Structa?

Structa is an Android document app built around one simple workflow: **scan a document, understand it, organize it, and use it**.

It combines document scanning, OCR (Optical Character Recognition), file organization, document editing and **Ask Structa** — an AI experience that answers questions using the content of your own documents as context.

## Preview

<table>
  <tr>
    <td width="50%"><img src="docs/images/01-home.webp" alt="Structa home screen — Scan. Organize. Done."></td>
    <td width="50%"><img src="docs/images/02-smart-ocr.webp" alt="Structa Smart OCR text extraction"></td>
  </tr>
  <tr>
    <td align="center"><strong>Scan. Organize. Done.</strong></td>
    <td align="center"><strong>Smart OCR</strong></td>
  </tr>
  <tr>
    <td width="50%"><img src="docs/images/03-files.webp" alt="Structa document library and organization"></td>
    <td width="50%"><img src="docs/images/04-edit-share.webp" alt="Structa document editor and sharing tools"></td>
  </tr>
  <tr>
    <td align="center"><strong>Organize your files</strong></td>
    <td align="center"><strong>Edit and share</strong></td>
  </tr>
</table>

<p align="center">
  <img src="docs/images/05-ask-structa.webp" alt="Ask Structa AI document questions with cited answers" width="72%">
</p>

## Key features

- **Document scanning** — Capture paper documents with your phone and turn them into digital files.
- **Smart OCR** — Extract selectable text from scanned documents and images.
- **Document library** — Keep files organized and easier to find from one place.
- **Edit & annotate** — Mark up documents, highlight important content and prepare them for sharing.
- **PDF workflow** — Convert documents to PDF and export or share the result.
- **Ask Structa** — Ask questions about a document and receive answers grounded in its content, with source references in the experience.

## How it works

1. **Scan** a paper document or bring in an existing file.
2. **Extract** useful text with OCR.
3. **Organize** the document in your Structa library.
4. **Edit, export or ask** Structa questions about the document.

Structa is designed to keep these steps inside one coherent workflow instead of making document scanning, OCR, organization and document Q&A feel like separate tools.

## Download & install

Structa is currently distributed as an Android APK.

1. Open the [latest release](https://github.com/de1t4s/Structa/releases/latest).
2. Download the `.apk` file from **Assets**.
3. On Android, allow installation from the browser or file manager you used to download it when prompted.
4. Open the APK and follow Android's installation flow.

**Minimum Android version:** Android 7.0 (API 24) or newer.

> [!TIP]
> Release notes include a SHA-256 checksum when provided. You can compare it with the downloaded APK to verify file integrity.

## Languages

Structa currently includes UI resources for:

**English · Spanish · French · Italian · German · Chinese · Japanese · Korean**

OCR capabilities can vary by document language, script, image quality and the recognition model available in the build.

## Privacy at a glance

Document scanning and OCR are designed to do as much work on-device as the feature allows. **Ask Structa requires an internet connection** and sends the document context needed for the request to a remote backend/AI service so an answer can be generated.

Structa may request access to the camera, documents/media and the internet when those capabilities are needed. See [PRIVACY.md](PRIVACY.md) for the current project-level privacy summary.

## Known limitations

- Structa is currently distributed outside Google Play, so Android may show a sideloading or Play Protect notice.
- Ask Structa and other network-backed features require an internet connection.
- OCR accuracy depends on scan quality, lighting, document layout, font and language/script support.
- Features and UI may change as Structa continues to evolve.

## FAQ

<details>
<summary><strong>Where should I download Structa?</strong></summary>

Only from this repository's [Releases](https://github.com/de1t4s/Structa/releases) page. This repository is the official public distribution hub.

</details>

<details>
<summary><strong>Is the source code public?</strong></summary>

No. This repository intentionally contains public-facing documentation, branding and release information only. Development source code and backend/debug material are kept in a separate private repository.

</details>

<details>
<summary><strong>Does Ask Structa work offline?</strong></summary>

No. Ask Structa is a network-backed feature and requires an internet connection.

</details>

<details>
<summary><strong>Why does Android warn me about installing the APK?</strong></summary>

Android warns users when an app is installed outside an app store. Always verify that the APK came from this repository's Releases page and, when available, compare its SHA-256 checksum with the release notes.

</details>

## Feedback & bug reports

Found a bug or have an idea? Use the repository's [Issues](https://github.com/de1t4s/Structa/issues) section.

Please avoid posting private documents, account data, API keys or other sensitive information in public issues.

## Repository scope

This repository intentionally contains only public distribution material:

- README and user-facing documentation
- Structa branding and promotional screenshots
- Privacy/security information
- Issue templates
- GitHub Releases and APK assets

It does **not** contain application source code, backend source code, development secrets, debug builds or private infrastructure configuration.

## License

Structa's application binaries, name, logo and branding are proprietary unless explicitly stated otherwise. See [LICENSE](LICENSE).

---

<div align="center">

**Structa** · *Your documents, understood.*

</div>
