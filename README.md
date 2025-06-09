# VS Code 익스텐션 개발 심층 스터디 (VS Code Extension Deep Dive)

![VS Code Logo](https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

본 레포지토리는 Visual Studio Code 확장 기능(Extension) 개발의 모든 것을 체계적으로 학습하고, 실제 동작하는 코드를 구현하며, 관련 지식을 공유하기 위해 만들어졌습니다. VS Code의 API 생태계를 이해하고 활용하는 것을 목표로합니다.

## 🎯 스터디 목표 (Our Goals)

* **VS Code 익스텐션 생태계 이해**: 익스텐션의 기본 구조, 생명주기(Lifecycle), 그리고 핵심 아키텍처를 완벽하게 이해합니다.
* **핵심 API 마스터**: `Commands`, `Workspace API`, `Window API` 등 가장 빈번하게 사용되는 API의 동작 원리와 활용법을 마스터합니다.
* **고급 기능 정복**: `Webview`, `Language Server Protocol (LSP)`, `Debug Adapter Protocol (DAP)`과 같은 고급 주제를 학습하고 직접 구현해 봅니다.
* **실전 경험 축적**: 실용적인 예제와 토이 프로젝트 개발을 통해 실제 문제 해결 능력을 기르고, 아이디어를 코드로 전환하는 경험을 축적합니다.
* **모범 사례 공유**: 성능 최적화, 테스트, 그리고 마켓플레이스 배포까지의 과정에서 필요한 모범 사례(Best Practices)를 논의하고 공유합니다.

## 📚 스터디 범위 (Scope of Study)

| 카테고리 (Category)    | 주제 (Topics)                                                                                                    |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Part 1: 기초 (Basics)** | `개발 환경 설정`, `익스텐션의 구조와 생명주기`, `Activation Events`, `Contribution Points`                       |
| **Part 2: 핵심 API (Core API)** | `Commands API`, `Window API (Notifications, Quick Picks)`, `Editor API (TextDocument, Decorations)`      |
| **Part 3: UI/UX 확장** | `Status Bar Item`, `Side Bar (Tree View)`, `Webview API`를 활용한 커스텀 UI/UX 구현                               |
| **Part 4: 고급 주제 (Advanced)** | `Language Server Protocol (LSP)`을 통한 언어 지원, `Debug Adapter Protocol (DAP)`, `Custom Data Formats` |
| **Part 5: 배포 및 관리 (DevOps)** | `테스팅 (Unit & Integration Tests)`, `패키징 (vsce)`, `마켓플레이스 배포`, `CI/CD 자동화`                  |
| **Part 6: Continue Clone** | [Continue](https://github.com/continuedev/continue/) 구조 이해 및 Clone 코딩딩            |

## 🛠️ 기술 스택 및 키워드 (Tech Stack & Keywords)

`Visual Studio Code API`, `TypeScript`, `Node.js`, `Extension`, `Language Server Protocol (LSP)`, `Debug Adapter Protocol (DAP)`, `Webview`, `Tree View`, `vsce`

## 🚀 진행 내역