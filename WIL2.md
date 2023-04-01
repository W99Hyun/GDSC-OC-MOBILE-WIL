# GDSC-OC-MOBILE-WIL
WIL2

1. main.dart에 코드 짜기

 import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

이 부분 빼고 delete

stless 후 탭 누르기

class MyApp//여기에 MyApp 입력// extends StatelessWidget {
  const MyApp({Key? key}) : super(key: key);
  @override
  Widget build(BuildContext context) {

    return MaterialApp // 여기에 MaterialApp 입력 // (
      home: // home: 입력 후 여기다 코드 짜기
      )
    );

  }
}
 
2. 위젯
 (1) Text('안녕')
 (2) Icon(Icons.star)
 (3) Image.asset('//이미지 경로')
  -> 파일 이름에서 우클릭-> New -> Diretory -> assets 로 만들기 -> 여기에 이미지 넣기
  -> pubspec.yaml 에 이미지 등록 -> 중간쯤 flutter 에
     flutter:
      assets:
       - assets/
    
    main 에서 
     Image.asset('assets/dog.png')
 (4)
   Center(
    child: Container( width: 50, height: 50, color : Color.blue)
   )
   
질문:
 1. stless 가 무엇인가?
 2. 국비 부트캠프 같은 것들에 대해 어떻게 생각하시는지 궁금합니다.
    
    
       
