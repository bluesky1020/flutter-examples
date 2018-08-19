# Flutter Snippets
A curated collection of most frequently used flutter snippets


- [Widgets](#widgets)
  - [Stateless](#stateless)
  - [StatefulWidget](#statefulwidget)
- [Utilities](#utilities)

## Widgets

### Stateless

Creates StatelessWidget
```dart
class name extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Container();
  }
}
```
Creates SingleChildScrollView
```dart
SingleChildScrollView(
  controller: controller,
  child: Column(),
),
```
Creates StreamBuilder
```dart
StreamBuilder(
  stream: stream ,
  initialData: initialData ,
  builder: (BuildContext context, AsyncSnapshot snapshot){
    return Container();
  },
),
```
### StatefulWidget
Creates StatefulWidget
```dart
class StatefulWidget extends StatefulWidget{
  StatefulWidgetState createState()=>  StatefulWidgetState();
}

class StatefulWidgetState extends State<StatefulWidget> {
  @override
  Widget build(BuildContext context){
    return Container();
  }
}
```
Creates StatefulBuilder
```dart
StatefulBuilder(
  builder: (BuildContext context, setState) {
    return Container();
  },
),
```

## Utilities

Creates Color Utils
```dart
class AppColors {
  static const Color colorPrimary = Color.fromARGB(255, 51, 51, 51);
  static const Color colorPrimaryDark = Color.fromARGB(255, 41, 41, 41);
  static const Color colorAccent = Color.fromARGB(255, 30, 198, 89);
  static const Color yellow = Color.fromARGB(255, 252, 163, 38);
  static const Color orange = Color.fromARGB(255, 252, 109, 38);
  static const Color grey_unselected = Color.fromARGB(255, 96, 96, 96);
  static const Color white_card = Color.fromARGB(255, 250, 250, 250);
  static const Color chrome_grey = Color.fromARGB(255, 240, 240, 240);
  static const Color white = Color.fromARGB(255, 255, 255, 255);
  static const Color white_secondary = Color.fromARGB(255, 220, 220, 220);
  static const Color white_un_selected = Color.fromARGB(255, 180, 180, 180);
  static const Color indigo = Color.fromARGB(255, 51, 105, 231);
  static const Color primary_text = Color.fromARGB(255, 51, 51, 51);
  static const Color secondary_text = Color.fromARGB(255, 114, 114, 114);
  static const Color grey = Color.fromARGB(255, 188, 187, 187);
}
```

