# 문제 : 프린터

1. 이해
    - priorities :  문서의 중요도가 순서대로 담긴 배열로 대기목록이다.
    - location : 내가 요청한 인쇄물의 인덱스
    - return : 내가 요청한 인쇄가 몇번째에 인쇄되는지
    - 인쇄 되는 방법
        - 인쇄목록에서 가장 앞의 인쇄물을 뺀다.
        - 나머지 인쇄목록에 방금 뺀 인쇄물의 우선순위 보다 높은 우선순위가 존재하면 방금뺀 인쇄물을 인쇄목록의 마지막으로 보낸다.
        - 없으면 방금 뺀 인쇄물을 인쇄한다.
2. 계획
    - 인쇄목록에서 가장 앞의 인쇄물의 우선 순위를 뽑는다.
    - 나머지 인쇄목록에 방금 뺀 우선순위 보다 높은 인쇄물이 있다면 인쇄목록의 가장 뒤로 보내준다.
    - 방금뺀 우선 순위보다 높은 인쇄물이 없다면 출력한다. 출력횟수를 증가시킨다.
    - 만약 우리가 원하는 인쇄물이 나왔다면 출력횟수를 출력해준다.
3. 실행
4. 회고