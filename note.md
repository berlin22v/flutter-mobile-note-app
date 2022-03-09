import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(debugShowCheckedModeBanner: false, home: MyApp()));
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      floatingActionButton: FloatingActionButton(
        onPressed: () {},
        tooltip: 'Increment Counter',
        child: const Icon(Icons.add),
        backgroundColor: Color(0xff0E44E1),
      ),
      backgroundColor: const Color(0xffFDFDFD),
      appBar: AppBar(
        centerTitle: true,
        backgroundColor: const Color(0xff0E44E1),
      ),
      body: Padding(
        padding: EdgeInsets.all(20),
        child: Column(
            crossAxisAlignment: CrossAxisAlignment.start,
         
            children: [
              Row (
                children: [
              Text(
                "Notes",
                style: TextStyle(
                  color: Color(0xff0E44E1),
                  fontSize: 30,
                  fontWeight: FontWeight.bold,
                  fontFamily: "ReemKufi",
                ),
              ),
              Spacer(),
             
              Icon(
  Icons.search_outlined,
                 color: Color(0xff0E44E1),
      size: 25.0,
),
                  Icon(
  Icons.more_vert_outlined,
                     color: Color(0xff0E44E1),
      size: 35.0,
),
          ],  
             ),
            ],
           
         
         
       ),
       
        ),
     
    );
  }
}
