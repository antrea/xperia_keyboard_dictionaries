# Xperia Keyboard language packs

Verified language-pack archive for the discontinued Sony Xperia Keyboard / SwiftKey SDK integration.

##XDA Thread

[APP][MOD] Xperia Keyboard 8.1.A.0.12 – T9 Fix & Dictionary Fix

https://xdaforums.com/t/app-mod-xperia-keyboard-8-1-a-0-12-t9-fix-dictionary-fix.4796648/

## Contents

- `LanguagePackages/`: 76 original language-pack ZIP archives.
- `SHA1SUMS.txt`: SHA-1 digest of every archive, in the format expected by the keyboard index.
- `languagePacksSSL.json`: compatible download index. This file is intentionally added in a second commit, after the archive commit hash is known.

## Integrity and provenance

The 76 archives were copied from:

- Repository: `karferz/XperiaKeyboardLanguagePacks`
- Source commit: `0c1c1977294e684a6d21bd85e1f696dc81916c84`

Every archive was compared byte-for-byte through its SHA-1 digest with the live Xperia community mirror index on 2026-07-30. All 76 digests matched.

The archive paths and names must not be changed because Xperia Keyboard obtains them from `languagePacksSSL.json`.

## Notice

These binary language models originate from the discontinued Sony Xperia Keyboard / SwiftKey SDK distribution. No ownership or additional license over the original binaries is claimed by this repository. This preservation copy is provided for compatibility with already-distributed software.
