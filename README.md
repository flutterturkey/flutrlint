# Flutter Turkey Lint (flutrlint)

[![pub package][pub_badge]][badge_link]
![style: flutrlint][style_badge]

Language: [English](README.md) | [Türkçe](README-TR.md)

The special lint package that we used on Flutter Turkey projects.

You can use this package on all your projects.

> **Note**: You can access more info about Lint Rules from [here](https://dart-lang.github.io/linter/index.html).

## Usage

To use these rules add the package below the `dev_dependencies` in the `pubspec.yaml` file.

```yaml
dev_dependencies:
  flutrlint: ^3.0.0
```

Create a file named `analysis_options.yaml` on the root directory of the project and add the command below.

```yaml
include: package:flutrlint/analysis_options.yaml
```

## Information

We added the lint rules we love as [Flutter Turkey](https://www.twitter.com/Flutter_Turkiye) into this package.

We also noted as a **comment** on top of it why we did not add the rule.

[pub_badge]: https://img.shields.io/pub/v/flutrlint.svg
[style_badge]: https://img.shields.io/badge/style-flutrlint-blue.svg
[badge_link]: https://github.com/flutterturkey/flutrlint
