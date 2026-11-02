# sprint-lab

**프로젝트 방법론 (2) 특강** 실습 저장소입니다. 가상 서비스의 개선 프로젝트를 스프린트 하나로 끝까지 진행합니다.

코드는 쓰지 않습니다. 고치는 대상은 Markdown 문서이고, Git 작업은 모두 GitHub 웹 화면에서 합니다.

## 프로젝트

**청년 지원금 AI 판정 서비스 v1.1 개선.** 지금 운영 중인 v1.0의 문서는 [service](service/) 폴더에 있습니다. 먼저 [프로젝트 소개](project/brief.md)를 읽으세요.

강의 슬라이드: [PDF](slides/project-method-2.pdf)

## 시작하기 (5교시, 팀별 1회)

1. 이 저장소 오른쪽 위 **Use this template(이 템플릿 사용)** → **Create a new repository(새 저장소 만들기)**
2. 팀장 계정을 Owner로, 이름은 `sprint-팀이름`, 공개 범위는 **Public(공개)** 으로 만듭니다.
3. 팀 저장소의 **Settings(설정) → Collaborators(협업자)** 에서 팀원을 초대합니다.
4. [Git Flow 안내](guides/03-git-flow.md)대로 `develop` 브랜치와 보호 규칙을 만듭니다.

> 공개 저장소입니다. 이름, 연락처 같은 개인 정보를 적지 마세요.

## 교시별 진행

| 교시 | 주제 | 안내서 | 결과물 |
| --- | --- | --- | --- |
| 1 | 시작과 시나리오 | [프로젝트 소개](project/brief.md) | 팀 이름, 역할 |
| 2 | 협업 도구 셋업 | [도구 셋업](guides/01-tools-setup.md) | Jira 프로젝트, Confluence 공간, Slack 채널 |
| 3 | WBS | [WBS 양식](project/wbs-template.md) | 팀 WBS |
| 4 | 일정 관리 | [일정 양식](project/schedule-template.md), [백로그](project/backlog.md) | Gantt Chart, 스프린트 계획 |
| 5 | Git Flow | [Git Flow 안내](guides/03-git-flow.md) | 팀 저장소, `feature` 브랜치 |
| 6 | PR과 코드 리뷰 | [PR과 리뷰 규칙](guides/04-pr-review.md) | 리뷰를 거친 PR |
| 7 | 가상 스프린트 | [스프린트 진행](guides/05-sprint.md), [기록 양식](project/sprint-log-template.md) | 릴리스 v1.1 |
| 8 | 리뷰와 회고 | [KPT 양식](project/retro-kpt-template.md) | 개선 이슈 |

3·4교시 안내는 [WBS와 일정 안내](guides/02-wbs-schedule.md)에도 있습니다.

## 폴더 구성

```text
sprint-lab/
├── service/        # 수정 대상: 서비스 문서 v1.0
├── project/        # 프로젝트 소개, 백로그, WBS·일정·회고 양식
├── guides/         # 교시별 안내서
├── slides/         # 강의 슬라이드 PDF
├── CHANGELOG.md    # 릴리스 노트
└── .github/        # PR 양식, Jira 대체용 이슈 양식
```
