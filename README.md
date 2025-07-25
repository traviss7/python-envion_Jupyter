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

# 🧠 LangChain LLM 테스트 예제

이 저장소는 OpenAI의 GPT-4 모델을 LangChain으로 호출해 간단한 질문에 답하는 테스트 코드입니다.

## 📁 파일 구성

- `test_llm.py`  
  OpenAI GPT-4 모델에 프롬프트를 보내고 응답을 출력하는 메인 실행 파일

## ⚙️ 사전 준비

1. Python 3.10 이상 설치
2. 필수 패키지 설치:

```bash
pip install langchain langchain-community openai
