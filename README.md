# Week 8 Midterm Test (중간고사)

지침을 읽고 다음 프로그램을 작성해 보세요. 그런 다음 프로그램을 컴파일하고 실행하여 원하는 출력이 생성되는지 확인합니다. 수업에서 했던 것처럼 프로그램을 GitHub(GitHub Desktop 사용)에 업로드하세요.

1. `abs_calc.c`
2. `gugudan.c`
3. `samyukgu.c`

---

## 1. abs_calc.c

C 라이브러리 함수(`abs()` 불사용)를 사용하지 않고 숫자의 절대값만 사용하여 결과를 계산하는 계산기 프로그램을 작성합니다. 다음 값에 대해 테스트하십시오.

```c
-5 + -6 = 11 // 예상 결과
-4 - -7 = -3 // 예상 결과
-8 * 2  = 16 // 예상 결과
-9 / 3  = 3  // 예상 결과
```

**힌트:**

- 우리가 3주차에 만든 계산기 코드 (`math.c`)를 시작점으로 사용하세요.
- `if` 문을 사용하고 숫자가 0보다 작으면 -1을 곱하여 부호를 변경하세요.

---

## 2. gugudan.c

11부터 19까지의 곱셈표를 출력하는 C 프로그램을 작성하세요. 1부터 9까지의 값을 곱하세요. 예: `11 * 1, 11 * 2, ... 11 * 9`, 그런 다음 `12 * 1` 등.

**힌트:** 두 개의 `for` 루프를 사용하세요. 첫 번째는 변수 1에 대한 것이고 두 번째는 변수 2에 대한 것입니다.

```c
// 예상 결과
11 * 1 = 11
11 * 2 = 22
11 * 3 = 33
...
11 * 9 = 99
12 * 1 = 12
...
19 * 7 = 133
19 * 8 = 152
19 * 9 = 171
```

---

## 3. samyukgu.c

1부터 100까지의 숫자를 출력하는 수정된 3-6-9 게임 프로그램을 C로 작성하세요. 그러나 숫자의 10번째 위치가 아닌 **1의 위치에만** 3, 6, 9가 있을 때마다 숫자 대신 "짝"을 출력합니다.

예를 들어: 이 프로그램은 30, 60, 90 모두에 대해 "짝"을 출력하지 않아야 합니다. 33, 36, 39, 63, 66, 69, 93, 96, 99 등의 경우 "짝"만 출력해야 합니다.

**힌트:** 모듈러스 연산자(%)와 `if` 문을 사용하여 숫자 열에 3, 6 또는 9가 있는지 판단하세요.

```c
// 예상 결과
1 2 짝 4 5 짝 7 8 짝 10 11 12 짝 ... 30 31 32 짝 34 35 짝 37 ... 100
```
