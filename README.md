# Flutter Turkey Lint (flutrlint)

[![style: flutrlint][badge]][badge_link]

The special lint package that we used on Flutter Turkey projects.

You can use this package on all your projects.

> **Note**: You can access more info about Lint Rules from [here](https://dart-lang.github.io/linter/index.html).

## Usage

To use these rules add the package below the `dev_dependencies` in the `pubspec.yaml` file.

```yaml
dev_dependencies:
  flutrlint: ^2.0.0
```

Create a file named `analysis_options.yaml` on the root directory of the project and add the command below.

```yaml
include: package:flutrlint/analysis_options.yaml
```

## Information

We added the lint rules we love as [Flutter Turkey](https://www.twitter.com/Flutter_Turkiye) into this package.

We also noted as a **comment** on top of it why we did not add the rule.

---

# Flutter Türkiye Lint (flutrlint)

[![style: flutrlint][badge]][badge_link]

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

[badge]: https://img.shields.io/badge/style-flutrlint-blue.svg
[badge_link]: https://github.com/flutterturkey/flutrlint