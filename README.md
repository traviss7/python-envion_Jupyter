# python-envion_Jupyter
# VS Code로 파이썬 실행 위한 작업 환경 만들기

이 저장소는 VS Code를 기반으로 파이썬 환경을 구성하고, Jupyter Notebook에서 시각화 테스트 및 LangChain 설치까지 완료한 과정을 기록한 것입니다. 
생성형 AI 실습이나 LangChain 기반 프로젝트를 진행할 수 있도록 기초적인 개발환경을 구축합니다.

---

## ✅ 1. 개발 환경 구성

- **IDE**: Visual Studio Code
- **Python 버전**: 3.11.7
- **확장 설치**
  - Jupyter (Microsoft)
  - Python (Microsoft)
- **가상환경 생성**
  ```bash
  python -m venv .venv
  source .venv/Scripts/activate  # (Windows)
