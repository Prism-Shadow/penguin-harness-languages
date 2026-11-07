# Changelog

All notable changes to the packages in this repository are documented here.
The five packages version together: one version, one release on GitHub, one
entry here, with the changes per package under it.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [0.0.3] — 2026-11-06

Card-quality release: every package's card carries a full name, an official icon and
a Chinese readme.

### @penguinharness/language-csharp

- `penguin.title` full form: "C# Language Support" (「C# 语言支持」) — the card shows
  the full name instead of the bare language short name.
- Official C# logo shipped as `icon.svg` and declared as `penguin.icon`.
- `README.zh.md` added: the package documents itself in both languages.

### @penguinharness/language-dart

- Full card titles ("Dart Language Support" / 「Dart 语言支持」), the official Dart
  icon as `penguin.icon`, and a `README.zh.md` — same shape as the C# package.

### @penguinharness/language-kotlin

- Full card titles ("Kotlin Language Support" / 「Kotlin 语言支持」), the official
  Kotlin icon as `penguin.icon`, and a `README.zh.md` — same shape as the C# package.

### @penguinharness/language-swift

- Full card titles ("Swift Language Support" / 「Swift 语言支持」), the official Swift
  icon as `penguin.icon`, and a `README.zh.md` — same shape as the C# package.

### @penguinharness/language-typst

- Full card titles ("Typst Language Support" / 「Typst 语言支持」), the official Typst
  icon as `penguin.icon` (a 128×128 PNG; rendering uses the harness's PNG icon support),
  and a `README.zh.md` — same shape as the C# package.

## [0.0.2] — 2026-11-04

The first published release, one GitHub release for the whole repository
(`v0.0.2`), with the packed tarball of every package attached.

### @penguinharness/language-csharp

- C# syntax highlighting for PenguinHarness: grammar, aliases, file extensions and the
  generated manifest table agree, per the contributions tests.
- The package manifest carries the RFC-0003 penguin fields (title, description,
  short_description, category, preinstall, quick_start, and the Chinese interface fields).
- The entry exports a named `activate` alongside the default plugin, so the plugin index
  can read it statically.

### @penguinharness/language-dart

- Dart syntax highlighting, same shape as the C# package: contributions tests, RFC-0003
  penguin fields, named `activate` export.

### @penguinharness/language-kotlin

- Kotlin syntax highlighting, same shape as the C# package: contributions tests, RFC-0003
  penguin fields, named `activate` export.

### @penguinharness/language-swift

- Swift syntax highlighting, same shape as the C# package: contributions tests, RFC-0003
  penguin fields, named `activate` export.

### @penguinharness/language-typst

- Typst syntax highlighting, same shape as the C# package: contributions tests, RFC-0003
  penguin fields, named `activate` export.

## [0.0.4] — 2026-11-07

Bilingual delivery release: the Chinese readme actually ships this time, and the
card gains a Chinese description.

### All five packages

- `files` whitelist now lists `README.zh.md` — 0.0.3 declared a Chinese readme but
  the packer silently dropped it, so the published tarball was English-only.
- `penguin.description_zh` added to each card: the Chinese description beside the
  English one, matching the `title` / `title_zh` pairing from 0.0.3.

### @penguinharness/language-csharp

- Version 0.0.4, rebuild with both `README.md` and `README.zh.md` in the tarball.

### @penguinharness/language-dart

- Version 0.0.4, rebuild with both `README.md` and `README.zh.md` in the tarball.

### @penguinharness/language-kotlin

- Version 0.0.4, rebuild with both `README.md` and `README.zh.md` in the tarball.

### @penguinharness/language-swift

- Version 0.0.4, rebuild with both `README.md` and `README.zh.md` in the tarball.

### @penguinharness/language-typst

- Version 0.0.4, rebuild with both `README.md` and `README.zh.md` in the tarball.

[0.0.4]: https://github.com/Prism-Shadow/penguin-harness-languages/releases/tag/v0.0.4
[0.0.3]: https://github.com/Prism-Shadow/penguin-harness-languages/releases/tag/v0.0.3
[0.0.2]: https://github.com/Prism-Shadow/penguin-harness-languages/releases/tag/v0.0.2
