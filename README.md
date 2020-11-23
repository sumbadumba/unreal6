# unreal6


constant는 상수이다

pawn은 기본적으로 움직이는 것 (캐릭터)
controller - 

// 숙제
1. 이번 시간에 작업했던 레벨 블루프린트를 연다.
2. 새로운 변수를 선언하고 이름은 MylntCounter로 설정한다.
   그리고 타입은 Integer로 설정하고 기본값은 5로 한다.
3. MylntCounter를 이벤트 그래프에 추가하고 + 노드의 두 번째에 연결한다.
4. Set Mylnteger 노드 이후에 이 값이 2000보다 큰지(〉=) 체크하도록 한다.
   블루프린트 컨텍스트 메뉴의 검색 바에서 integer〉=를 입력하면 integer >= integer를 볼 수 있다.
   이것을 이벤트 그래프에 추가한다. 이 노드는 O(false) 또는 l(true)을 반환한다.
5. B integer 데이터 핀을〉= 노드에 연결하고 값은 2000으로 설정한다.
6. 분기 노드Branch node를 사용해 조건이 참true인지 거짓false인지 검사한다.
   >= 노드의빨간색 데이터 핀에서 드래그해 블루프린트 컨텍스트 메뉴를 띄운다.
   그리고 검색바에서 Branch# 입력하고 선택해 분기 노드를 추가한다.
7. Set Mylnteger 노드의 출력 실행 핀을 분기 노드의 입력 실행 핀에 연결한다.
8. 분기 노드의 True를 드래그해 블루프린트 컨텍스트 메뉴를 띄운 후 검색 바에서
   set myinteger를 입력하고 Set Mylnteger를 선택해 이벤트 그래프에 노드를 추가한다.
9. Set Mylnteger의 값은 0으로 설정한다.
10. 이제 커스텀 이벤트를 만들 차례다. 이벤트 그래프 아래쪽의 빈 공간에서 마우스 오른쪽 버튼을 누른 후
   블루프린트 컨텍스트 메뉴를 띄운다. 그리고 검색 바에서 custom을 입력하고 Add Custom Event를 선택한다.
   커스텀 이벤트의 이름은 MyCustomEvent로 설정한다.
11- MyCustomEvent 노드의 출력 실행 핀을 드래그해 블루프린트 컨텍스트 메뉴를 띄우고 검색 바에서 print를
   입력한 후 Print String을 선택해 노드를 추가한다.
