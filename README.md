# Flutter Türkiye Lint (flutrlint)

Flutter Türkiye projelerinde kullandığımız özel lint paketi.

Bu paketi, bütün Flutter projelerinizde kullanabilirsiniz.

[![style: flutrlint][badge]][badge_link]

---

> **Note**: This package is heavily inspired by and has a dependency on [pedantic](https://github.com/dart-lang/pedantic).

Lint Kuralları hakkında daha fazla bilgiye [bu bağlantı](https://dart-lang.github.io/linter/index.html) ile ulaşabilirsiniz.

## Kullanım
Kuralları kullanmak için aşağıdaki komutu `pubspec.yaml` dosyası içerisinde bulunan `dev_dependencies`'in altına ekleyin.

```yaml
dev_dependencies:
  flutrlint:
    git:
      url: git://github.com/flutterturkey/flutrlint.git
```

Projenizin ana dizinine `analysis_options.yaml` isimli bir dosya oluşturun ve içerisine aşağıdaki komutu ekleyin.

```yaml
include: package:flutrlint/analysis_options.yaml
```

## Bilgi
Bu lint paketi içerisinde ekip içerisinde en sevdiğimiz link kurallarını ekledik.

Dahil etmediğimiz lint kurallarını neden dahil etmediğimizi **yorum** olarak ilgili kuralın üzerine yazdık.

[badge]: https://img.shields.io/badge/style-flutrlint-blue.svg
[badge_link]: https://github.com/flutterturkey/flutrlint
