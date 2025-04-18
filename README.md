# dizest_MCP
>dizest workflow Automation Tools with agent, MCP
---

## Demo
[![Video](https://img.youtube.com/vi/22ftoUcyLh8/0.jpg)](https://youtu.be/22ftoUcyLh8)
> 클릭하면 유튜브로 넘어가요 중간에 실행 시간이 길기 때문에 적당히 넘겨보셈 ㅋ
---

## 필수 환경
| 항목 | 버전 / 링크 | 비고 |
|------|-------------------------------|------|
| **dizest** | <https://github.com/season-framework/dizest> | 프레임워크 핵심 |
| **dizest LLM server (MCP client)** | <https://github.com/NowDoor/dizest_MCP_client/tree/main> | LLM 응답 시스템이 들어가 있는 Dizest workflow |

**Tip:** 추가적인 의존성(예: Python 버전, OS, Docker 등)이 있다면 이 섹션에 함께 기재하세요.

---

## 설치
```
pip install dizest_MCP 
```
## 실행 방법
```
export TAVILY_API_KEY={Your TAVILY_API_KEY}
export export OPENAI_API_KEY= {Your OPENAI_API_KEY}
dizest_MCP
```
---
## Dizest 설치 및 환경 구성
MCP server - client 모두 열어 놓는 것이 좋다
```
pip install dizest
cd {Your directory}
dizest install {Your project Name}
dizest run #port 4000 다른 포트 지정시 --port '포트번호'를 적어주면 된다
```
web 접속 후 해당 ip:port로 접속
웹 상에서 MCP client 파일을 넣어주거나 '{Your directory}/{Your project Name}/data'의 경로에 삽입하면 된다.

---
## 기여
1. 기여자 없음 ㅠ

---

## 라이선스
MIT License — 자세한 내용은 [LICENSE](LICENSE) 파일을 참고하세요.

---

## 연락처
- **Email**: bijou@season.co.kr

> 프로젝트가 도움이 되었다면 ⭐️ Star 를 눌러주세요!

