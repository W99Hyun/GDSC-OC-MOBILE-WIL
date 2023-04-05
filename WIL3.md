# GDSC-OC-MOBILE-WIL3

MaterialApp-> 구글이 제공하는 앱 스타일
Cupertino-> 아이폰 앱 스타일

Scaffold(
  appBar: AppBar(), // 상
  body: Container(), // 중
  BottomNavigationBar: BottomAppBar(), // 하
)

Row( // 가로, 세로는 Column
  mainAxisAlignment: MainAxisAlligment.center // 가운데 자동 정렬
                                      .spaceEvenly // 일정한 간격 정렬
                     CrossAxisAlignment // 반대 정렬, Row이니 세로 정렬
  children: [
    Icon(Icons.star)
    Icon(Icons.star)
  ]
)
