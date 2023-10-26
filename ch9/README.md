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

- flex-start = 교차 축 시작 (defalt값일때 상단부터)
- center = 교차 축 중심
- flex-end = 교차 축 끝

flex-direction : 기본축을 정함(defalt는 row임)

- row = 가로
- row-reverse = 가로 역순
- column = 세로
- column-reverse = 세로 역순
