# dizest_MCP
> dizest workflow Automation Tools with agent, MCP
---

## Demo
여기에 데모를 적을 예정

---

## 필수 환경
| 항목 | 버전 / 링크 | 비고 |
|------|-------------------------------|------|
| **dizest** | <https://github.com/season-framework/dizest> | 프레임워크 핵심 |
| **dizest LLM server (MCP client)** | **(추후 공개)** | 서버 주소 미정 |

> **Tip:** 추가적인 의존성(예: Python 버전, OS, Docker 등)이 있다면 이 섹션에 함께 기재하세요.

---

## Installation/설치
```
pip install dizest_MCP 
```
## execution/실행 방법
export TAVILY_API_KEY={Your TAVILY_API_KEY}
export export OPENAI_API_KEY= {Your OPENAI_API_KEY}
dizest_MCP

---

## 설정

```

---

## 실행 방법
```bash
# 개발 서버 실행
$ python -m your_package.app --config config.yaml

# 프로덕션 모드 (예: gunicorn)
$ gunicorn your_package.app:app -c gunicorn.conf.py
```

REST API 엔드포인트 예시:
```http
GET /healthz  -> 200 OK
POST /v1/inference  -> JSON 결과 반환
```

---

## 예제
```python
from your_package import Client

client = Client(api_key="<YOUR_KEY>")
response = client.infer(prompt="안녕?")
print(response)
```

| 입력 | 출력 |
|-------|-------|
| "안녕?" | "안녕하세요! 무엇을 도와드릴까요?" |

---

## 기여
1. 이슈 또는 PR 생성 전에 [CONTRIBUTING.md](CONTRIBUTING.md)를 확인해주세요.
2. 기능 추가 시 반드시 테스트 케이스를 포함해주세요.
3. `pre-commit` 훅을 사용하여 코드 스타일을 유지합니다.

---

## 라이선스
MIT License — 자세한 내용은 [LICENSE](LICENSE) 파일을 참고하세요.

---

## 연락처
- **Maintainer**: [@yourhandle](https://github.com/yourhandle)
- **Email**: you@example.com
- **Slack**: #your-project

> 프로젝트가 도움이 되었다면 ⭐️ Star 를 눌러주세요!

