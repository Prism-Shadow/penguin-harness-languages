# Changelog

All notable changes to the packages in this repository are documented here.
The five packages version together: one version, one release on GitHub, one
entry here, with the changes per package under it.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

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

[0.0.2]: https://github.com/Prism-Shadow/penguin-harness-languages/releases/tag/v0.0.2
