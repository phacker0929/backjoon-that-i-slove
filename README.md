# Algorithm Practice

백준과 프로그래머스에서 해결한 알고리즘 문제를 사이트, 언어, 문제별로 정리한 저장소입니다. 자동 업로드된 정답과 직접 작성한 풀이를 함께 보존하며, 같은 문제를 다른 방식으로 푼 경우 파일명을 구분했습니다.

## 저장소 구조

```text
solutions/
├── baekjoon/
│   ├── python/
│   │   └── 문제번호-문제명/
│   └── c/
│       └── 문제번호-문제명/
└── programmers/
    └── python/
        └── 문제번호-문제명/
```

- `solution.py`, `solution.c`: 기본 풀이
- `solution-local.py`: 직접 올렸던 별도 풀이
- `solution-two-pointers.py`: 풀이 전략을 이름으로 구분한 대안 풀이
- 문제 폴더의 `README.md`: 문제 링크, 분류와 자동 채점 정보 또는 간단한 학습 메모

## 문제 목록

### 백준 · Python

| 문제 | 핵심 내용 | 풀이 |
| --- | --- | --- |
| 1000 A+B | 입력, 형 변환, 사칙연산 | [보기](solutions/baekjoon/python/1000-A+B/solution.py) |
| 1009 분산처리 | 나머지, 거듭제곱 주기 | [보기](solutions/baekjoon/python/1009-분산처리/solution.py) |
| 10171 고양이 | 문자열 출력, 이스케이프 문자 | [보기](solutions/baekjoon/python/10171-고양이/solution.py) |
| 1032 명령 프롬프트 | 문자열 비교 | [보기](solutions/baekjoon/python/1032-명령-프롬프트/solution.py) |
| 10818 최소, 최대 | 리스트, 최솟값과 최댓값 | [보기](solutions/baekjoon/python/10818-최소-최대/solution.py) |
| 10828 스택 | 스택, 명령 처리 | [보기](solutions/baekjoon/python/10828-스택/solution.py) |
| 10869 사칙연산 | 기본 연산자 | [보기](solutions/baekjoon/python/10869-사칙연산/solution.py) |
| 10988 팰린드롬인지 확인하기 | 슬라이싱, 문자열 뒤집기 | [보기](solutions/baekjoon/python/10988-팰린드롬인지-확인하기/solution.py) |
| 1330 두 수 비교하기 | 조건문 | [보기](solutions/baekjoon/python/1330-두-수-비교하기/solution.py) |
| 1546 평균 | 리스트 변환, 평균 | [보기](solutions/baekjoon/python/1546-평균/solution.py) |
| 18258 큐 2 | 덱, 큐 | [보기](solutions/baekjoon/python/18258-큐-2/solution.py) |
| 1920 수 찾기 | 정렬, 이분 탐색 | [보기](solutions/baekjoon/python/1920-수-찾기/solution.py) |
| 2343 기타 레슨 | 이분 탐색, 매개 변수 탐색 | [보기](solutions/baekjoon/python/2343-기타-레슨/solution.py) |
| 2439 별 찍기 - 2 | 반복문, 출력 정렬 | [보기](solutions/baekjoon/python/2439-별-찍기-2/solution.py) |
| 2480 주사위 세개 | 다중 조건문 | [보기](solutions/baekjoon/python/2480-주사위-세개/solution.py) |
| 2525 오븐 시계 | 시간 계산, 나머지 | [보기](solutions/baekjoon/python/2525-오븐-시계/solution.py) |
| 2743 단어 길이 재기 | 문자열 길이 | [보기](solutions/baekjoon/python/2743-단어-길이-재기/solution.py) |
| 2744 대소문자 바꾸기 | 문자열 순회, 대소문자 변환 | [보기](solutions/baekjoon/python/2744-대소문자-바꾸기/solution.py) |
| 2750 수 정렬하기 | 리스트 정렬 | [보기](solutions/baekjoon/python/2750-수-정렬하기/solution.py) |
| 3273 두 수의 합 | 집합, 두 포인터 | [집합 풀이](solutions/baekjoon/python/3273-두-수의-합/solution.py) · [두 포인터 풀이](solutions/baekjoon/python/3273-두-수의-합/solution-two-pointers.py) |
| 9012 괄호 | 문자열, 스택 개념 | [보기](solutions/baekjoon/python/9012-괄호/solution.py) |

### 백준 · C

| 문제 | 핵심 내용 | 풀이 |
| --- | --- | --- |
| 10828 스택 | 배열 기반 스택, 문자열 명령 처리 | [보기](solutions/baekjoon/c/10828-스택/solution.c) |
| 9012 괄호 | 문자열 순회, 괄호 균형 | [보기](solutions/baekjoon/c/9012-괄호/solution.c) |

### 프로그래머스 · Python

| 문제 | 핵심 내용 | 풀이 |
| --- | --- | --- |
| 43238 입국심사 | 이분 탐색, 매개 변수 탐색 | [보기](solutions/programmers/python/43238-입국심사/solution.py) |

## 학습 내용

문제 풀이에서 확인되는 개념과 다음 복습 항목은 [학습 내용 정리](docs/learning-summary.md)에 모았습니다.

새 문제를 직접 추가하거나 백준허브를 계속 사용할 때의 규칙은 [풀이 추가 방법](docs/adding-solutions.md)을 참고합니다.

## 정리 원칙

- 기존 풀이 로직은 학습 기록으로 보존합니다.
- 같은 내용의 중복 파일은 하나로 통합합니다.
- 실행 화면과 압축 파일 대신 텍스트 소스 코드를 관리합니다.
- 앞으로 추가하는 문제도 `사이트/언어/문제번호-문제명` 구조를 따릅니다.
- 자동 채점 결과가 기록된 문제와 로컬에서만 작성한 문제를 구분합니다.

## 현재 검증 범위

Python 파일의 문법 검사를 수행하며, 대표 입력으로 확인 가능한 문제는 간단한 실행 검사를 추가합니다. 과거에 직접 올린 모든 풀이가 현재 문제의 전체 테스트를 통과한다고 보장하지는 않습니다.
