# GDSC-OC-MOBILE-WIL
#WIL1

1. Just in compile(짠 코드를 화면에서 바로 확인 가능)
   a head of time compile 가능(flutter에서 최적화하고 싶은 부분이 있으면 직접 최적화 가능)

2. 함수 안에서 지역변수 선언, 메소드 안에서 지역변수 선언-> var 사용(컴파일러가 타입 알아서 앎)

3. dynamic-> 자료형이 결정되어 있지 않은 자료형(정말 필요할 때만 쓰기)

4. null safety-> 개발작 null값을 참조할 수 없게 하는거
   String? nico='nico'; -> String 뒤에 ? 붙이기
   nico=null; // 컴파일 가능-> 컴파일러가 nico가 string 일 수도, null 일 수도 알기 때문
   nico?.isNotEmpty; -> nico가 null인지 아닌지 확인해보고 함수 돌려줌

5. final => const 랑 동일(초기화할 때 한번만 설정 가능)

6. last -> var, final 앞에 쓰고, 초기 데이터 없이 선언할 수 있게 해줌
   last final name;
   name ='nico';
   
7. const -> 변경 안되는 건 final과 동일하나, 컴파일 될 때 값을 알아야 함
   final은 앱을 올린 후에 사용자 닉네임같은 거 저장이 가능하나,
   const는 컴파일 될 때 값을 알아야 하므로 값을 모르며 앱 자체 실행을 할 수 없음

##질문
1. Swift 와 flutter 의 차이점이 무엇인지
2. 현재 위의 두 언어 중 어떤 언어가 ios 개발에 더 인기가 있는지
