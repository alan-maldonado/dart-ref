# prompter_am

```dart
import 'package:prompter_am/prompter_am.dart';

void main() {
  final options = [
    new Option('I want red', '#f00'),
    new Option('I want blue', '#00f'),
  ];

  final prompter = Prompter();

  String colorCode = prompter.askMultiple('Select the color', options);
  bool answer = prompter.askBinary('Do you like this lib?');

  print(colorCode);
  print(answer);
}
```
