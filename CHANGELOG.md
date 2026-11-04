# Changelog

All notable changes to the packages in this repository are documented here.
Each package versions independently; entries are grouped by package and version.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/);
every package starts at 0.0.1 and versions independently after that.

## [@penguinharness/language-csharp]

### [0.0.1] — 2026-11-03

First release.

- C# syntax highlighting for PenguinHarness: grammar, aliases, file extensions and the
  generated manifest table agree, per the contributions tests.
- The package manifest carries the RFC-0003 penguin fields (title, description,
  short_description, category, preinstall, quick_start, and the Chinese interface fields).
- The entry exports a named `activate` alongside the default plugin, so the plugin index
  can read it statically.

## [@penguinharness/language-dart]

### [0.0.1] — 2026-11-03

First release. Same shape as `@penguinharness/language-csharp` 0.0.1: Dart grammar,
RFC-0003 penguin fields, named `activate` export.

## [@penguinharness/language-kotlin]

### [0.0.1] — 2026-11-03

First release. Same shape as `@penguinharness/language-csharp` 0.0.1: Kotlin grammar,
RFC-0003 penguin fields, named `activate` export.

## [@penguinharness/language-swift]

### [0.0.1] — 2026-11-03

First release. Same shape as `@penguinharness/language-csharp` 0.0.1: Swift grammar,
RFC-0003 penguin fields, named `activate` export.

## [@penguinharness/language-typst]

### [0.0.1] — 2026-11-03

First release. Same shape as `@penguinharness/language-csharp` 0.0.1: Typst grammar,
RFC-0003 penguin fields, named `activate` export.

[@penguinharness/language-csharp]: https://github.com/Prism-Shadow/penguin-harness-languages/tree/main/plugins/language-csharp
[@penguinharness/language-dart]: https://github.com/Prism-Shadow/penguin-harness-languages/tree/main/plugins/language-dart
[@penguinharness/language-kotlin]: https://github.com/Prism-Shadow/penguin-harness-languages/tree/main/plugins/language-kotlin
[@penguinharness/language-swift]: https://github.com/Prism-Shadow/penguin-harness-languages/tree/main/plugins/language-swift
[@penguinharness/language-typst]: https://github.com/Prism-Shadow/penguin-harness-languages/tree/main/plugins/language-typst

[0.0.1]: https://github.com/Prism-Shadow/penguin-harness-languages/releases?q=language-&tag=language-csharp%2Fv0.0.1
