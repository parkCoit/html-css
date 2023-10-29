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

transition-time-function 속성
-transition을 세밀하게 타이밍을 조절할 수 있음
-개발자 도구(f12) 들어간 후 transition에서 화살표 ease옆에 보라색버튼 들어가서 조절


애니메이션

@keyframes : 키프레임
-키프레임은 어떤 속성이 어떻게 바뀔지 명시함
-from블록에는 애니메이션이 시작될때 속성 추가
-to블록에는 애니메이션 끝날 때 속성 추가

animation-name : 이름; 키프레임 이름
-키프레임을 만들었으면 만든 키프레임 선택 후 재생해야함.
-어떤 키프레임 선택할지 지칭하는 속성

animation-duration : 5s; 지속 시간 
-애니메이션 지속 시간을 설정 할 수 있음

animation-iteration-count : infinite; 반복 횟수
-애니메이션 반복 횟수 정함.
-infinite로 설정하면 무한으로 반복

animation-direction : alternate; 방향
애니메이션이 끝난 후 역재생하게 만들어 자연스럽게

animation-fill-mod : both; 종료 후 모드
-both로 설정하면 애니메이션 종료된 후 변화를 유지

animation-delay: 4s; 대기시간
-애니메이션 재생하기 전에 대기 시간 추가

animation-timing-function: 타이밍 함수
-개발자 도구에서 타이밍 함수 편집하고 적용 가능