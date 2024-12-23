# stateful_stateless_widgets

This project demonstrates the differences between **StatelessWidget** and **StatefulWidget** in Flutter by building a simple counter app in two versions.

## Project Structure

1. **StatelessWidget Version**  
   The `MyStatelessApp` demonstrates a counter app implemented using a `StatelessWidget`. In this version:
   - The UI remains static.
   - Clicking the "Increment" button does not change the counter value because a `StatelessWidget` cannot manage state.

2. **StatefulWidget Version**  
   The `MyStatefulWidgetApp` showcases the same counter app using a `StatefulWidget`. In this version:
   - The `setState` method is used to dynamically update the counter value and rebuild the UI.

## Observations

- **StatelessWidget**  
  - Suitable for UI elements that do not require state changes (e.g., static screens, decorative widgets).
  - Cannot react to user interactions that need state updates.

- **StatefulWidget**  
  - Ideal for interactive elements where state changes dynamically (e.g., forms, counters, toggles).
  - Uses the `setState` method to trigger UI updates when state changes.

## Cara Menjalankan Aplikasi
 ```bash
   flutter run //jalankan kode ini pada terminal 
 ```
   
## Cara Beralih Antara Versi StatelessWidget dan StatefulWidget

### Untuk StatelessWidget:
Pastikan baris berikut di file `main.dart` **tidak dikomentari**:
```dart
runApp(MyStatelessApp());
```

### Untuk StatefulWidget:
Pastikan baris berikut di file `main.dart` **tidak dikomentari**:
```dart
runApp(MyStatefulWidgetApp());
```
