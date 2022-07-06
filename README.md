# Curved Bottom Navigation Bar

### Add Dependency
```bash
dependencies:
  curved_navigation_bar: ^1.0.3 #latest version
```
## Sample
<p><img align="center" src="https://github.com/Vishwa-Karthik/Flutter_Curved_NavigationBar/blob/master/1.gif" width=600 height=150 />
<p/>

### Code
```dart
Scaffold(
  bottomNavigationBar: CurvedNavigationBar(
    backgroundColor: Colors.blueAccent,
    items: <Widget>[
      Icon(Icons.add, size: 30),
      Icon(Icons.list, size: 30),
      Icon(Icons.compare_arrows, size: 30),
    ],
    onTap: (index) {
      //Handle button tap
    },
  ),
  body: Container(color: Colors.blueAccent),
)
```

### Reference
Pub.dev : [curved_navigation_bar](https://pub.dev/packages/curved_navigation_bar)
