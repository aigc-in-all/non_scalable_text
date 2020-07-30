# non_scalable_text

A Flutter package for Text Widget that does not scale with the system font size.

## Usage

To use this plugin, add `non_scalable_text` as a [dependency in your pubspec.yaml file](https://flutter.dev/platform-plugins/).

### Example

``` dart
import 'package:flutter/material.dart';
import 'package:non_scalable_text/non_scalable_text.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Container(
        child: Center(
          child: NonScalableText('Example Content'),
        ),
      ),
    );
  }
}
```
