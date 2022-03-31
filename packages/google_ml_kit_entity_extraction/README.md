# Google's ML Kit On-Device Translation for Flutter

[![Pub Version](https://img.shields.io/pub/v/google_ml_kit)](https://pub.dev/packages/google_ml_kit)

A Flutter plugin to use [Google's ML Kit Entity Extractor API](https://developers.google.com/ml-kit/language/entity-extraction).

## Getting Started

Before you get started read about the requirements and known issues of this plugin [here](https://github.com/bharat-biradar/Google-Ml-Kit-plugin).

## Usage

#### 1. Create an instance of Entity Extractor

```dart
final entityExtractor = (EntityExtractorOptions.english);
```

#### 2. Process text

```dart
final List<EntityAnnotation> response = await entityExtractor.extractEntities(text);
```

#### 3. Release resources with `close()`

```dart
entityExtractor.close();
```

## Example app

Look at this [example](https://github.com/bharat-biradar/Google-Ml-Kit-plugin/tree/master/packages/google_ml_kit/example) to see the plugin in action.

## Contributing

Contributions are welcome.
In case of any problems look at [existing issues](https://github.com/bharat-biradar/Google-Ml-Kit-plugin/issues), if you cannot find anything related to your problem then open an issue.
Create an issue before opening a [pull request](https://github.com/bharat-biradar/Google-Ml-Kit-plugin/pulls) for non trivial fixes.
In case of trivial fixes open a [pull request](https://github.com/bharat-biradar/Google-Ml-Kit-plugin/pulls) directly.