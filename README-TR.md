# Flutter Türkiye Lint (flutrlint)

[![pub package][pub_badge]][badge_link]
![style: flutrlint][style_badge]

Language: [English](README.md) | [Türkçe](README-TR.md)

Flutter Türkiye projelerinde kullandığımız özel lint paketi.

Bu paketi, bütün Flutter projelerinizde kullanabilirsiniz.

> **Not**: Lint Kuralları hakkında daha fazla bilgiye [bu bağlantıyla](https://dart-lang.github.io/linter/index.html) ulaşabilirsiniz.

## Kullanım

Kuralları kullanmak için aşağıdaki komutu `pubspec.yaml` dosyası içerisinde bulunan `dev_dependencies`'in altına ekleyin.

```yaml
dev_dependencies:
  flutrlint: ^2.0.0
```

Projenizin ana dizinine `analysis_options.yaml` isimli bir dosya oluşturun ve içerisine aşağıdaki komutu ekleyin.

```yaml
include: package:flutrlint/analysis_options.yaml
```

## Bilgi

Bu lint paketi içerisinde [Flutter Türkiye](https://www.twitter.com/Flutter_Turkiye) ekibi olarak en sevdiğimiz lint kurallarını ekledik.

Dahil etmediğimiz lint kurallarını neden dahil etmediğimizi ilgili kuralın üzerine **yorum** olarak yazdık.

[pub_badge]: https://img.shields.io/pub/v/flutrlint.svg
[style_badge]: https://img.shields.io/badge/style-flutrlint-blue.svg
[badge_link]: https://github.com/flutterturkey/flutrlint
