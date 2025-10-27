# Python Project Template

이 템플릿은 FastAPI 기반 또는 ML 프로젝트용 Python 환경을 빠르게 세팅하기 위한 기본 구조입니다.

## 포함 내용
- `black`, `isort`, `ruff`, `pre-commit` 자동 포맷팅
- `conda` 환경 (`environment.yml`)
- 기본 `src/`, `tests/` 구조
- `pytest` 테스트 환경
- GitHub push 시 자동 pre-commit 훅

## 사용법
1. GitHub에서 “Use this template” 클릭 → 새 repo 생성
2. 로컬에서 클론
   ```bash
   git clone https://github.com/<YOUR_ID>/<NEW_REPO>.git
   cd <NEW_REPO>
   conda env create -f environment.yml
   conda activate <NEW_REPO>
   pre-commit install
