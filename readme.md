탬버린즈 웹사이트 제작을 통해서 반응형 웹페이지 제작을 연습하였습니다.

우선 헤더 부분은 position: fixed를 사용하여 상단 고정되게 하였고 메뉴들은 
flex를 통하여 수평 정렬을 하였습니다. 또한 화면 크기가 줄어들면서 
display:none을 통하여 메뉴들이 보이지 않게 처리하였습니다.

mainbanner 부분 또한 사람 이미지와 향초가 나오는 동영상을 수평 정렬하기 위하여
display: flex를 사용하였고 동영상은 video태그를 사용하여 삽입하였습니다.
자세히 보면 사람 이미지 부분에 위 아래가 살짝 어두운 것을 보실 수 있는데
이는 person-img 태그 앞 부분에 ::before 가상 요소 선택자를 추가하였는데
linear-gradient를 사용하여 은은하게 어두운 효과를 주었고 position: absolute를
활용하여 이미지 위에 나타날 수 있게 하였습니다. 또한 모바일에서는 가상 요소 선택자에
display: none을 적용하여 어두운 효과를 제거하였습니다.

모바일 반응형에서는 메인배너 부분에 수직정렬을 위하여 display: flex을 
display: block으로 변경하였습니다. 
