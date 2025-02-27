# 💻 알고리즘 학습 소모임 - 40th Study Cafe

- 해당 저장소는 '40th Study Cafe'의 알고리즘 학습 소모임을 위해 만들어졌습니다.
- 알고리즘 공부를 본격적으로 시작하지 않았으나 시작하고 싶으신 분들에게 도움을 드리기 위해 만들었습니다.
- 알고리즘 풀이 레퍼런스 코드는 해당 단계의 풀이 기간이 지난 직후 해당 저장소에 공유해드립니다.

#### 부족한 안내와 정보이지만 스터디원분들의 알고리즘 학습에 도움이 되시길 바랍니다.

<hr />

#### 40기 스터디 화이팅! 본인을 믿으세요!

#### 당장은 어렵게 느껴지더라도! 멈추지 않는다면!

#### 본인도 모르는 사이에 성장하고 있을겁니다!

<hr />

## 📃 목차

1. [알고리즘이란](#알고리즘이란)
2. [알고리즘을 잘 공부하는 법](#알고리즘을-잘-공부하는-법)
3. [코딩 테스트 잘 보는 법](#코딩-테스트-잘-보는-법)
4. [좋은 코드를 만드는 법](#좋은-코드를-만드는-법)
5. [자료구조](#자료구조)
6. [백준 알고리즘 사이트 가이드](#백준-알고리즘-사이트-가이드)
7. [소모임 진행 방식](#소모임-진행-방식)
8. [1주차 OT](#1주차-OT)

<hr />

## 알고리즘이란

### 개요

- 특정 문제를 효율적이고 빠르게 해결하는 것이 궁극적인 목표입니다.
- 정해진 일련의 절차나 방법을 공식화한 형태로 표현한 것입니다.
- 개발자의 정체성이 되어줄 기초 코딩 능력입니다.

### 문제해결 능력 (=일머리)

- 논리적사고
- 전산화 능력 (현실에 있는 것을 컴퓨터의 세계에서 구현하는 것)
- 엣지 케이스 탐색 (예외 사항을 잘 찾는 능력)

### 알고리즘은 변하지 않습니다.

- 다이스트라 알고리즘은 1956년에 나온 알고리즘이지만 아직도 사용됩니다.

<hr />

## 알고리즘을 잘 공부하는 법

### 문제를 풀 때 중요한 것

1. 항상 **여러가지 풀이 방법**이 있을 수 있다는 것을 기억하자
2. 항상 **예외가 있을 수 있다는 것**을 기억하자
3. 내가 풀어낸 답이 **베스트인지 의심**하자
4. 문제를 풀었다면 **시행착오를 모두 기록**하자
5. **다른 사람의 코드**를 많이 보자. 생각하지 못했던 방법을 발견할 수 있다.
6. 쉽게 포기하지 말자. 하지만 **도저히 모르겠다면 답을 보는 것**도 좋은 방법이다.

### 그나마 재밌게 공부하는 법

1. 공부하는 알고리즘이 어디에 쓰일지 생각해보면서 공부하자

### 마음가짐

1. 알고리즘 마스터가 될 필요는 없다.

   - 회사는 업무 수행 할 수 있는 **기초 능력**을 확인하고 싶을 뿐이다.
   - 하지만 알고리즘이 중요한 회사에 지원한다면 많이 공부해야 한다. (게임회사)

2. 즉, **어디까지 공부할지** 정하는 것이 중요하다.

<hr />

## 코딩 테스트 잘 보는 법

### 자신의 성향을 파악하자

1. 내 어떤 사람인지 알아야 한다.
   - 미리 생각하고 의사 코드를 작성해야 더 잘 풀리는 사람
   - 일단 코드를 작성하면서 생각해야 더 잘 풀리는 사람

### 메모하기

1. 긴장하면 내가 풀다가 내가 무엇을 하려 했는지 잊을 수 있다.

   - 코드에 주석을 달거나 노트에 메모하면서 풀자.

2. 알고리즘은 눈리적으로 표현할 수 있다.
   - 헷갈리면 순서도를 그리면서 정리해보자.

### 디버깅은 필수

1. 내가 예상한대로 동작이 안된다면 꼭 디버깅을 하자(디버거?, runJS 등)
   - 로직 중간에 `console.log` 를 사용하여 값이 정상인지 확인 할 수 있다.
   - 외부 IDE 사용이 가능하다면 Node.js 의 디버그 모드를 사용하자.

### 익숙해지기

1. 문제를 잘 읽는 것에 익숙해져야 한다.

   - 수능에서 언어, 외국어 지문을 읽듯이

2. 시간복잡도를 계산하는 것에 익숙해져야 한다.

   - 자잘자잘한 성능보다 시간복잡도가 훨씬 중요하다.

3. 항상 엣지 케이스를 생각하는 것에 익숙해져야 한다.

<hr />

## 좋은 코드를 만드는 법

### 간결하고 가독성 좋은 코드

1. 변수, 함수의 이름을 잘 정했는가?
2. 중복코드를 제거했는가?
3. 함수형 프로그래밍도 좋은 방법
   - map, filter, reduce 와 같은 고차함수 이용

### 가지치기를 했는가?

1. 흔히 가지치기는 백트래킹과 같은 알고리즘에서 사용되지만 그 외 알고리즘에서도 중요하다.
2. 사소한 로직이라면 성능이 크게 개선되지는 않지만 코드 리뷰에서 좋은 평가를 받을 수 있다.

### 자바스크립트를 잘 이용했는가?

1. 자바스크립트로 코딩 테스트를 본다면 문법을 잘 활용해야 한다.
   - 구조 분해 할당
   - Spread 오퍼레이터

### 일관성을 유지했는가? (**중요한내용**)

1. 잘 짰더라도 일관성 없는 코드보다 조금 더러워도 일관성 있는 코드가 좋다.
   - var 와 let 혼용 ❌
   - snake_case 와 camelCase 혼용 ❌
   - 변수명, 함수명을 줄임말로 쓰다가 어딘가에선 전부 적는 경우 ❌
   - 제출전에 코드 스타일이나 변수명, 함수명을 꼭 확인하자 ✅

<hr />

## 자료구조

### 개요

- **특정구조**를 이루고 메모리 효율적 사용, 안정적 데이터 처리를 목표로 사용됩니다.
- 원차원인 컴퓨터 메모리를 현실에 대응되도록 구조를 만든 것입니다.

### 종류

1. 단순 구조

   - 정수
   - 실수
   - 문자열
   - 논리

2. 선형 구조 : 한 원소 뒤에 하나의 원소만이 존재하는 형태입니다.
   ![](https://velog.velcdn.com/images/hyeonwooga/post/4bcae410-e5a4-4313-ab2a-1752adad6dc6/image.png)

   - 배열
   - 연결 리스트
   - 스택
   - 큐

3. 비선형 구조 : 원소간 다대다 관계를 가지는 구조로 계층적 구조나 망형 구조를 표현하기에 적절한 형태입니다.
   ![](https://velog.velcdn.com/images/hyeonwooga/post/edc06aad-ef59-4e7f-80c2-cea040143648/image.png)
   - 트리
   - 그래프

### 완벽한 자료구조는 없다

- 우열하거나 열등하 자료구조는 없습니다.
- 특정 상황에서 유용한 자료구조와 덜 유용한 자료구조가 존재할 뿐입니다.
- 상황에 맞게 적절한 자료구조를 선택하면 됩니다.

<hr />

## 백준 알고리즘 사이트 가이드

### 개요

- <a href="https://www.acmicpc.net/" target="_blank">백준 사이트</a> `문제 -> 단계별로 풀어보기` 의 문제를 풀이합니다.
- 간혹 JavaScript(node.js) 로 풀이가 안되는 문제가 있는 경우 넘어갑니다.

### 문제풀이 일정

| 주차  | 날짜                | 단계        | 문제 갯수 |
| ----- | ------------------- | ----------- | --------- |
| 1주차 | 22.08.22 - 22.08.28 | 1단계       | 15문제    |
| 2주차 | 22.08.29 - 22.09.04 | 2단계       | 7문제     |
| 3주차 | 22.09.05 - 22.09.11 | 3단계       | 13문제    |
| 4주차 | 22.09.12 - 22.09.18 | 4단계+5단계 | 9문제     |
| 5주차 | 22.09.19 - 22.09.25 | 6단계       | 10문제    |
| 6주차 | 22.09.26 - 22.10.02 | 9단계       | 5문제     |

### 백준에서 입력과 출력

- 입력을 코플릿처럼 함수형으로 매개변수를 받는 것이 아니고 txt 파일을 입력받는 개념입니다.
- 그래서 입력값을 받기위해 'fs' 모듈 혹은 'readLine' 모듈을 사용해야합니다. - 'fs' 모듈 사용을 권장드립니다.
- 출력을 코플릿처럼 return 반환값;으로 주는 것이 아닌 console.log(반환값); 으로 출력하는 개념입니다.

### fs 모듈 사용 예시

![](https://velog.velcdn.com/images/hyeonwooga/post/84a9a361-d1da-4f95-a4c2-1d89446a5f55/image.png)

- 예제 입력 : '1 2'가 쓰여있는 txt 파일이라고 생각하시면 됩니다.
- 예제 출력 : 구글 크롬 개발자탭 콘솔에 찍히는 출력입니다.

- 예제 코드

  - 입력

  ```javascript
  const fs = require("fs"); // fs 모듈 불러오기
  const input = fs.readFileSync("/dev/stdin").toString(); // input === '1 2';
  ```

  - 데이터 정제

  ```javascript
  const input = fs.readFileSync("/dev/stdin").toString().split(" ").map(Number); // input === [1, 2];
  ```

  - 출력

  ```javascript
  console.log(input[0] + input[1]);
  ```

fs 모듈에 대한 추가 내용은 <a href="https://nyang-in.tistory.com/156" target="_blank">🖐여기서🖐</a> 확인부탁드립니다.

<hr />

## 소모임 진행 방식

### 일정

- 총 6주로 진행됩니다.
- 매주 월요일 아침 8시에 해당 주에 대한 가이드 및 지난주 리뷰 진행합니다. (필참 ❌)
  - 1주차만 화요일 아침 8시에 진행합니다. (2022.08.23 AM 08:00) (필참 ❌)

### 문제풀이

- 안내드린 문제들을 날짜에 맞게 각자 풀이하시면 됩니다.
- 안내드린 일정과 본인의 일정을 잘 조율하여 부담없이 풀이하시면 됩니다.
- 질문 및 소통은 `40기 스터디 카페` 디스코드에서 진행합니다.

### 참여조건 (권장 ✅)

1. 해당 저장소를 `Star` || `Fork` 합니다.
2. `40기 스터디카페` == 참여중 ? OK : `40기 스터디카페` 디스코드에 참여합니다.

<hr />

## 1주차 OT

### 알고리즘 소모임의 목적, 만든 이유

- 알고리즘은 경험할수록 늘기때문에 경험을 많이 하시도록 권장해드리고 싶었습니다.

### 알고리즘 소모임 전체 진행 흐름

- 제가 대략적인 가이드를 드리지만 본인이 주도적으로 학습하시는 겁니다.
- 초반에는 쉬우실 수 있습니다.
- 알고리즘 학습 습관을 만드시고 알고리즘 학습에 익숙해진다고 생각하시고 성실하게 임해주세요.

### 백준 사이트

- UI, 문제 제출방식 등이 불편합니다.
- 하지만 문제가 많고 단계별로 잘 나누어져 있습니다.
- 구글링시 레퍼런스가 많아서 다양하게 참고할 수 있습니다.

#### 저도 UI/UX 때문에 정말 하기 싫었었지만 지나고 보니 지금 도움이 정말 많이 됩니다.

### 백준 1단계 1번, 3번 풀어보기

- 입출력이 코플릿과 다르기 때문에 적응해야합니다.
- RunJS, VSCode 등 다른 IDE 에서 문제를 풀고 백준에서는 제출만 하는 것을 추천드립니다.

<hr />
