transform(변형) : 이 속성은 요소를 변형시킴.
-변형은 폭과 높이 색깔,소리 등 모든 것을 변형시킨다

-transform: rotate(회전단위);
회전의 단위에는 deg(각도), rad(라디안) - 호의길이 , turn(회전 수)

-transform: rotateX, rotateY, rotateZ
위 함수를 이용하여 축을 바꾸어 회전을 시킬 수 있음 (deg(각도)로 가능)


-transform: translate(X, Y); - 위치
X가 증가할수록 왼쪽에서 멀어지고, Y가 증가할수록 상단으로부터 멀어짐

-transform: scale(크기); - 크기
값이 1일 때는 원본크기, 2일 때는 두 배가 된다.


transition(전환 효과) : 색이 변하고, 요소가 회전하는 등 모든 요소 바꿀 수 있음
예시 - transition: 5s; - 5초동안 모든 속성 전환, 배경색만 - background-color 5s