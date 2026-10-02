<div align="center">

<img src="docs/images/structa-logo.webp" alt="Structa logo" width="170">

# Structa

### Scan. Organize. Done.

**Your documents, understood.**

[![Latest Release](https://img.shields.io/github/v/release/de1t4s/Structa?display_name=tag&sort=semver&label=release)](https://github.com/de1t4s/Structa/releases/latest)
![Android](https://img.shields.io/badge/Android-7.0%2B-3DDC84?logo=android&logoColor=white)
![Distribution](https://img.shields.io/badge/distribution-APK-0B7BA8)
![Source](https://img.shields.io/badge/source-private-555)

**[Download Structa from GitHub Releases](https://github.com/de1t4s/Structa/releases/latest)**

</div>

> [!IMPORTANT]
> This is Structa's **official public distribution repository**. Source code, backend code, development configuration and debug material are maintained privately. Android builds are distributed through [GitHub Releases](https://github.com/de1t4s/Structa/releases).

## Your documents, understood

Structa is an Android document app built around a simple workflow: **scan, understand, organize and use your documents**.

Instead of treating scanning, OCR, file management, editing and document Q&A as unrelated tools, Structa brings them together in one app.

<p align="center">
  <img src="docs/images/01-home.webp" alt="Structa home screen — Scan. Organize. Done." width="820">
</p>

## Smart OCR

**Turn scanned documents and images into usable text.**

Structa uses OCR (Optical Character Recognition) to detect text inside documents. Recognized text can be selected and used for actions such as copying and searching, making paper documents far easier to work with digitally.

<p align="center">
  <img src="docs/images/02-smart-ocr.webp" alt="Structa Smart OCR — recognize, edit, copy and search text" width="820">
</p>

## Organize your files

**Keep your documents in one place and find them when you need them.**

The Structa library is designed around quick access to documents, folders and common file types. Search and filters help keep scanned documents from becoming another pile of files on your phone.

<p align="center">
  <img src="docs/images/03-files.webp" alt="Structa file library — organize and find documents" width="820">
</p>

## Edit and share

**Review a document, annotate what matters and export the result.**

Structa includes a document editing workflow for annotations and highlights, together with export and sharing actions. Documents can be prepared for PDF output or shared as part of the same flow.

<p align="center">
  <img src="docs/images/04-edit-share.webp" alt="Structa editor — annotate, highlight, convert and share documents" width="820">
</p>

## Ask Structa

**Ask questions about your own documents — and see where the answer came from.**

Ask Structa uses the content of the selected document as context for the conversation. The interface is designed to connect answers back to relevant document information instead of presenting an answer without context.

Examples include asking for a due date, an amount, a summary or specific information contained in a document.

<p align="center">
  <img src="docs/images/05-ask-structa.webp" alt="Ask Structa — AI answers grounded in document content with source references" width="820">
</p>

## How it works

1. **Scan** a paper document or bring in an existing file.
2. **Extract** useful text with Smart OCR.
3. **Organize** the document in your Structa library.
4. **Edit, export or share** it when needed.
5. **Ask Structa** questions about the document.

## Download & install

Structa is currently distributed as an Android APK through GitHub Releases.

1. Open the [latest release](https://github.com/de1t4s/Structa/releases/latest).
2. Download the `.apk` file listed under **Assets**.
3. Android may ask you to allow installs from your browser or file manager.
4. Open the downloaded APK and follow Android's installation flow.

**Minimum Android version:** Android 7.0 (API 24) or newer.

> [!TIP]
> When a release includes a SHA-256 checksum, you can compare it with the downloaded APK to verify file integrity.

## Languages

Structa currently includes UI resources for:

**English · Spanish · French · Italian · German · Chinese · Japanese · Korean**

OCR results can vary depending on the document language, script, image quality, layout and recognition support available in the build.

## Privacy at a glance

Document scanning and OCR are designed to perform as much processing on-device as the feature allows.

**Ask Structa requires an internet connection** and sends the document context needed for the request to a remote backend/AI service so an answer can be generated.

Structa may request access to the camera, documents/media and the internet when those capabilities are required. See [PRIVACY.md](PRIVACY.md) for the public privacy summary.

## Known limitations

- Structa is currently distributed outside Google Play, so Android may display a sideloading or Play Protect notice.
- Ask Structa and other network-backed functionality require an internet connection.
- OCR accuracy depends on scan quality, lighting, layout, font and language/script support.
- Features and UI may change as Structa continues to evolve.

## FAQ

<details>
<summary><strong>Where should I download Structa?</strong></summary>

Only from this repository's [Releases](https://github.com/de1t4s/Structa/releases) page.

</details>

<details>
<summary><strong>Is the source code public?</strong></summary>

No. This repository is intentionally dedicated to public-facing documentation, branding and releases. Application source code, backend code and debug/development material are maintained separately in a private repository.

</details>

<details>
<summary><strong>Does Ask Structa work offline?</strong></summary>

No. Ask Structa is a network-backed feature and requires an internet connection.

</details>

<details>
<summary><strong>Why can Android warn me when I install the APK?</strong></summary>

Android warns users when installing applications outside an app store. Verify that your APK came from this repository's Releases page and, when available, compare its SHA-256 checksum with the release notes.

</details>

## Feedback & bug reports

Found a bug or have an idea? Use [GitHub Issues](https://github.com/de1t4s/Structa/issues).

Please **do not attach private documents, credentials, API keys or sensitive account information** to a public issue.

## Repository scope

This public repository contains:

- User-facing documentation
- Structa branding and promotional images
- Privacy and security information
- Issue templates
- GitHub Releases and APK assets

It intentionally does **not** contain application source code, backend source code, development secrets, private infrastructure configuration or debug builds.

## License

Structa's application binaries, name, logo and branding are proprietary unless explicitly stated otherwise. See [LICENSE](LICENSE).

---

<div align="center">

**Structa** · *Your documents, understood.*

</div>
