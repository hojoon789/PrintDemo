
---

## 🔹 main_print_v1.py

기본적인 `print()` 사용법과 문자열 포맷팅 방법을 다룹니다.

- 기본 출력
- 여러 값 출력 (콤마 구분)
- f-string 활용 (Python 3.6+)
- `format()` 함수
- C 스타일 포맷팅 (`%`)
- 줄바꿈 / `end` / `sep` 옵션
- 딕셔너리 및 리스트 출력
- 계산식 내 삽입
- 멀티라인 f-string

---

## 🔹 main_print_v2.py

[`rich`](https://github.com/Textualize/rich) 라이브러리를 활용해 시각적으로 더 보기 좋은 출력을 제공합니다.

- 컬러/스타일 적용
- 패널(Panel) 출력
- 테이블(Table) 출력
- `sep`, `end` 옵션 지원 (`rich.print`와 호환)

---

## 🔹 requirements.txt

가상환경에서 사용된 모든 패키지 목록입니다.  

주요 패키지:
- `rich` : 컬러풀한 터미널 출력
- `jupyter` : 노트북 환경 실행
- `numpy`, `matplotlib` 등 (데이터 실습용)

---

## 🚀 실행 방법

1. 가상환경 생성 및 활성화
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Mac/Linux
   .venv\Scripts\activate      # Windows
