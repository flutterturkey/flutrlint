# flutrlint

Flutter Türkiye organizasyon projeleri için özel lint paketi.

[![style: flutrlint][badge]][badge_link]

---

**Note**: This package is heavily inspired by and has a dependency on [pedantic](https://github.com/dart-lang/pedantic).

Kuralları daha detaylı olarak [Linter for Dart](https://dart-lang.github.io/linter/index.html) sayfasından inceleyebilirsiniz.

## Usage

Kuralları kullanmak için `pubspec.yaml` dosyanıza aşağıdaki gibi dev dependencies'e ekleyin:

```yaml
dev_dependencies:
  flutrlint:
    git:
      url: git://github.com/flutterturkey/flutrlint.git
```

Ardından, `analysis_options.yaml` içerisine aşağıdaki satırı ekleyin:

```yaml
include: package:flutrlint/analysis_options.yaml
```

[badge]: https://img.shields.io/badge/style-flutrlint-blue.svg
[badge_link]: https://github.com/flutterturkey/flutrlint
