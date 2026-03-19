# 📚 Java Algorithm Solution Repository

자바(Java)를 이용한 알고리즘 문제 해결 역량을 기르고, 효율적인 풀이 과정을 기록하는 저장소입니다.

단순히 정답을 맞히는 것에 그치지 않고, 시간 복잡도 최적화와 효율적인 자료구조 활용을 고민하며 학습한 내용을 정리했습니다.

## 🛠️ Tech Stack

+ **Language**: Java (OpenJDK 17+)

+ **IDE**: IntelliJ IDEA

+ **Platform**: [Baekjoon](https://www.acmicpc.net/) / [Programmers](https://programmers.co.kr/)

+ **Leveling**: [Solved.ac](https://solved.ac/) ([Gold IV](https://github.com/Hasegos))

## 📖 Contents

### 1. 백준 알고리즘 (단계별로 풀어보기)

기초부터 심화 알고리즘까지 체계적으로 학습하고 있습니다.
+ 진행 현황: `Step 05. 문자열 ~ Step 32. 동적계획법과 최단거리 역추적`
+ 👉 [백준 알고리즘 상세 풀이 보기](./src/Baekjun/단계별로풀어보기/README.md)

### 2. Solved.ac (Class & Level)
Solved.ac 커리큘럼 기반의 필수 문제 및 난이도별(Gold/Silver) 문제 풀이입니다.
+ 구성: `Class` (핵심 역량) / `Level` (티어별 정복)
+ 👉 [Solved.ac 정리 보기](./src/Solved/README.md)

### 3. Programmers프로그래머스
플랫폼의 레벨별(Level 0, Level 1 등) 코딩테스트 연습 풀이입니다.
+ 👉 [Programmers 정리 보기](./src/Programmers/Level/README.md)

### 4. 정렬 알고리즘 심화
기초 정렬부터 Java의 `Dual-Pivot Quicksort` 원리 이해 및 커스텀 정렬 구현법을 정리합니다.
+ 👉 [정렬에 대한 이야기 보기](./src/정렬에대한이야기/README.md)

## ✍️ Repository Structure

```txt
.
└── src
    ├── Baekjun
    │     └── 단계별로풀어보기 (Step 05 ~ Step 32)
    ├── Solved
    │   ├── Class
    │   └── Level
    ├── Programmers
    │   └── Level (Zero, One, ...)
    └── 정렬에대한이야기
        └── Sorting_Examples.java
```

## 💡 Technical Approach

+ **Performance Optimization**: `Scanner` 대신 `BufferedReader`와 `StringTokenizer`를 사용하여 입출력 성능을 최적화하고,
대량 출력 시 `StringBuilder`를 활용합니다.

+ **Collection Framework**: `PriorityQueue`, `Deque`, `HashMap` 등 문제에 적합한 자료구조를 선택하여 시간 복잡도를 개선합니다.

+ **Algorithm Analysis**: 문제를 푼 후 반드시 시간 복잡도($O(N)$)와 공간 복잡도를 분석하여 최적의 로직인지 검토합니다.

+ **Clean Code & Reusability**: 가독성 높은 변수명 사용과 로직별 메서드 분리를 통해 실전 코딩테스트 환경에 대비합니다.