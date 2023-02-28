# All extensions

all extension available use many extension to your flutter app

## Installation

1. Add the latest version of package to your pubspec.yaml (and run`dart pub get`):

```yaml
dependencies:
  all_extensions: ^0.0.1
```

2. Import the package and use it in your Flutter App.

```dart
import 'package:all_extensions/all_extensions.dart';
```

```dart
class Allextensions extends StatelessWidget {
  const Allextensions({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
     list name = <String>[kapil , ishwar ,ishwar,ishwar nameera, moshin, nishant arvind , kapil , kapil];
        var duplicateremove = name.unique(
        (x) => x,
        );

    return MaterialApp(
      home: Scaffold(
        body: Center(
          child: ListView.builder(
            itemCount: name.length,
              itemBuilder: (context, i){

                  return ListTile(
                    title: Text("${name[i]}"),
                  );

              },
          ),
        )
      ),
    );
  }
}
```

## Features

all extension available use many extension

## Getting started

flutter list any duplicates data remove
ex :
list name = <String>[kapil , ishwar ,ishwar,ishwar nameera, moshin, nishant arvind , kapil , kapil];

var duplicateremove = name.unique(
(x) => x,
);
