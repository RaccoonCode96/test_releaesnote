# GitHub 관리

## 1. PR 관리

### PR 템플릿

- 참고
  - [Github Docs: Creating a pull request template for your repository](https://docs.github.com/en/enterprise-server@3.7/communities/using-templates-to-encourage-useful-issues-and-pull-requests/creating-a-pull-request-template-for-your-repository)
  - [StackOverFlow: 다중 PR 템플릿 선택하기](https://stackoverflow.com/questions/73771068/multiple-templates-for-pull-requests-on-github)

## 2. 릴리즈 노트 관리

- 참고
  - [카카오 엔터프라이즈: Release Note 톺아보기](https://tech.kakaoenterprise.com/113)

### 릴리즈 노트란?

- 서비스 출시 또는 업데이트 마다 이전과 다른 변경 사항을 체계적으로 정리하여 정보를 제공하는 문서
  - 기능 추가, 삭제, 버그 개선 등...

### 릴리즈 노트의 구성요소

1. 버전

- 알파(Alpha) => 베타(Beta) => 출시 후보(Release Candidate) => 출시(Release)
- [Semantic Versioning Specification (Semver)](https://semver.org/lang/ko/spec/v2.0.0.html) : MAJOR.MINOR.PATCH

2. 날짜

- 해당 문서가 얼마나 최신인지 보여주는 역할

3. 구분

- 태그(카테고리)를 구분하여 변경사항을 나타내면 사용자가 빠르게 내용을 파악할 수 있는데 도움을 준다.
- 구성: 최초, 기능, 변경, 수정, 중단

4. 설명

- 소프트웨어의 변경사항 기술
- 간략하고 집약적으로 작성(자세한 내용은 문서 링크 연결이 좋다.)

5. 작성 방법

- 간략하지만, 독자들에게 알맞은 정보를 작성하자.
  - 어떤 버그가 얼마나 개선되었는지
  - 어떤 기능이 어떻게 변경되었는지
  - 어떤 기능이 추가되었는지
- 짧게 장성하고 링크를 활용하라
- 일관된 용어를 사용하라.
- 사용자 관점에서 쉽게 작성하라.
- 시각적 효과(그룹화)를 적용하라.

## 릴리즈 노트 살펴보기

- [노션](https://www.notion.so/ko-kr/releases)
- [vscode](https://github.com/microsoft/vscode/releases)
- [slack](https://slack.com/intl/ko-kr/release-notes/windows)
- [Dooray](https://helpdesk.dooray.com/share/pages/9wWo-xwiR66BO5LGshgVTg/3179083034117533402)
