## 🚀 기능 요구 사항

배달이가 좋아하는 369게임을 하고자 한다. 놀이법은 1부터 숫자를 하나씩 대면서, 3, 6, 9가 들어가는 숫자는 숫자를 말하는 대신 3, 6, 9의 개수만큼 손뼉을 쳐야 한다.

숫자 number가 매개변수로 주어질 때, 1부터 number까지 손뼉을 몇 번 쳐야 하는지 횟수를 return 하도록 solution 메서드를 완성하라.

### 제한사항

- number는 1 이상 10,000 이하인 자연수이다.

### 실행 결과 예시

| number | result |
| ------ | ------ |
| 13     | 4      |
| 33     | 14     |

### 구현 목록

1. 1부터 number까지 반복문을 돌며 한자리로 잘개 쪼개 배열에 넣는다.
2. count 변수를 생성해 배열의 처음 부터 끝까지 3, 6, 9가 몇번 존재하는지 count한다.
3. count 변수를 return 한다.
