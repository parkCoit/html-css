display_flex
- 인라인처럼 텍스트의 크기만큼 폭을 차지함 하지만 다른 공간 좁다고 줄바꿈 되지 않음.
- 자기 자식 요소에게 강제적으로 정렬 요구
- 2개의 축으로 이루어져 있으며 세로가 교차축 가로가 기본축임

justify-content :

1.기본 축 설정
- flex-start = 아이템을 시작 쪽으로(기본적으로 왼쪽)
- center = 아이템을 중앙으로
- flex-end = 아이템을 끝 쪽으로(기본적으로 오른쪽)

2.아이템 사이 떨어트리는 범위
- space-between = 아이템끼리 최대한 거리두기
- space-around = 아이템 양옆에 같은 여백
- space-evenly = 아이템 사이 여백 크기 일치

align-items : 교차 축 설정(기본축은 flex-direction로 설정 defalt 값은 row )
                추가 적으로 defalt값이 stretch 여서 크기가 100%로 잡혀있음

- flex-start = 교차 축 시작 (defalt값일때 상단부터)
- center = 교차 축 중심
- flex-end = 교차 축 끝

flex-direction : 기본축을 정함(defalt는 row임)

- row = 가로
- row-reverse = 가로 역순
- column = 세로
- column-reverse = 세로 역순


gap 속성
justify-content속성은 축을 중심으로 하기 때문에 세세한 값 설정 x
세세하게 원하는 값만큼 간격 추가 시에 gap속성 사용
justify-content: space-between; 사용시 gap 무시 됨.






display_grid

grid-template-columns : 그리드의 열의 수와 폭을 고정할 수 있음 (단위 fr은 남은 그리드 공간 나누는 단위) 

1. grid-template-columns: 150px 150px 150px - 150px로 3개
2. grid-template-columns: 150px 1fr - 150px 그리고 남은 그리드 채움
3. grid-template-columns: repeat(3,1fr) - 1fr로 3개 나눔 repeat(횟수, 단위)
4. grid-template-columns: reapat(auto-fill, 150px) - 150px이 될 때까지 채움

gap : 그리드 아이템 사이 여백

row-gap : 행 간격 설정
cloumn-gap : 열 간격 설정


position 속성
포지션 속성은 left, right, top, bottom속성 사용

-position: relative; - 상대위치
현재 위치에서 약간 옮길 때 사용 상대적으로 얼마나 이동할지 정함
top: -15px; , left: 8px; - 상단기준 15px 당겨짐 , 왼쪽기준 8px 밀림

-position : absolute; - 절대 위치
absolute값은 요소를 절대 위치에 고정시킬 때 사용
top:0; , right:0; 오른쪽 상단에 고정

-position : fixed; - 고정 위치
요소를 브라우저에 고정시킬 때 사용
다른 콘텐츠를 보기 위해 스크롤을 내려도 그대로 고정 하고 싶은 요소 있을 때 (광고,메뉴 등등)

-position : sticky; - 흡착 위치
일반 요소들처럼 보이다 스크롤 내리면 광고 등이 고정위치처럼 따라오는 현상


z-index 속성 : 순서 설정
덮어 씌워지는 z축 순서 정하는 요소
여러 요소의 값을 z-index 값을 넣어 더 높은 값의 요소가 위에 온다 생각하면 됨.


