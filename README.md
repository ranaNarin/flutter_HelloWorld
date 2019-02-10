# flutter_HelloWorld

![screenshot 2019-02-10 at 2 51 29 pm](https://user-images.githubusercontent.com/13502470/52531965-85102f80-2d43-11e9-82b6-cf5973e32ef3.png)


import 'package:flutter/material.dart';

void main(){
  runApp(new MyApp());
}

class MyApp extends StatelessWidget{
  @override
  Widget build(BuildContext context) {

    return new MaterialApp(
      title: "My App",
      home: new Scaffold(
        appBar: new AppBar(
          title: new Text("Hello Page"),
        ),
        body: new Center(child: new Text("Hello World!")),
      )
    );
  }
}
