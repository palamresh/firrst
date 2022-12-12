# firrst
import 'package:flutter/material.dart';

class FirstPage extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return ListView(
      children: [
        ListTile(
          leading: Icon(Icons.abc_outlined),
          title: Text('this ia abc outline'),
        )
      ],
    );
  }
}

class Information extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Text("Information Page");
  }
}

class Services extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Text('Service Pages');
  }
}
