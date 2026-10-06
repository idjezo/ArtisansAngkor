# Artisans Angkor · project delivery

This branch contains an AES-256 password-protected delivery archive. Application sources and editorial reference documents remain encrypted. The password is provided separately in the private conversation and must not be committed here.

## Recover with a browser (no installation)

1. Download [Recuperer-ArtisansAngkor.html](https://github.com/idjezo/ArtisansAngkor/raw/refs/heads/aa-delivery/Recuperer-ArtisansAngkor.html), then open the downloaded file in a recent Chrome, Edge or Firefox browser.
2. Enter the archive password supplied privately and click **Créer mon ZIP classique**.
3. Save the resulting **ArtisansAngkor-editorial.zip**. If downloading does not start, click the download link shown on the page.
4. In Windows, right-click this resulting ZIP and choose **Extract All**, then follow the extracted README.md.

This self-contained HTML includes only the encrypted archive and the open-source zip.js library (license included). It decrypts locally, verifies the original ZIP SHA-256, and makes no external requests. It includes no password. This page is a file-recovery tool; the editorial application itself is inside the resulting project ZIP.

## Recover with an archive program

1. Open ArtisansAngkor-editorial-protected.zip on GitHub and use Download raw file.
2. Open it with 7-Zip, WinRAR or another tool supporting AES-encrypted ZIP archives.
3. Enter the password supplied privately. Extract ArtisansAngkor-editorial.zip.
4. Unzip the resulting project archive and follow its README.md.

The built-in Windows ZIP extractor may not support this encryption; use 7-Zip or WinRAR.

Protected archive SHA-256: 9a9d93f6c2b027a0a75b2d82d98d284c9a0e50c3453f0ad411599ec7c2a96e0b
Original project ZIP SHA-256: 271ecc148eeb3a7ce8a6204ddb40c23e1d0f41a09b51db7b595da87f4eab5988
