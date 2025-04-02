# GitHub Pull Request(PR) 실습 레포지토리

이 레포지토리는 CAT&DOG 스터디의 Git 및 GitHub Pull Request 실습을 위해 만들어졌습니다.

## Pull Request (PR) 보내는 방법

아래 절차를 따라 이 레포지토리에 본인의 이름과 GitHub 아이디를 추가하는 PR을 보내주세요.

1.  **Fork**: 이 레포지토리 우측 상단의 'Fork' 버튼을 눌러 본인의 GitHub 계정으로 이 레포지토리를 복제합니다.
2.  **Clone (선택 사항)**: 본인 계정으로 Fork한 레포지토리를 로컬 컴퓨터에 Clone합니다. (터미널 또는 GitHub Desktop 사용)
    ```bash
    git clone <fork한 레포지토리 URL>
    ```
    * *참고: 간단한 수정은 GitHub 웹사이트에서 직접 할 수도 있습니다.*
    * *참고: 위 URL은 예시입니다. 실제 URL은 본인의 GitHub 계정으로 Fork한 레포지토리에서 복사해오는 것을 권장합니다.*
3.  **Branch 생성 (선택 사항, 권장)**: 변경 사항을 위한 새 브랜치를 만듭니다.
    ```bash
    git checkout -b add-my-name
    ```
    * `add-my-name` 대신 원하는 브랜치 이름을 사용해도 됩니다.
4.  **README.md 파일 수정**: 이 `README.md` 파일을 열어 아래 '참여자 명단' 섹션에 본인의 이름과 GitHub 아이디를 추가합니다.
5.  **Commit & Push**: 변경 사항을 저장(Commit)하고, 본인의 Fork된 레포지토리로 Push합니다.
    ```bash
    git add README.md
    git commit -m "Add [본인 이름] to participant list"
    git push origin add-my-name
    ```
6.  **Pull Request 생성**:
    * 본인의 GitHub 계정으로 Fork한 레포지토리 페이지로 이동합니다.
    * 'Pull requests' 탭으로 이동하여 'New pull request' 버튼을 클릭합니다.
    * 변경 사항을 적용한 브랜치 (`add-my-name`)를 선택하고, 원본 레포지토리 (`KU-CATDOG/how-to-pr`)의 `main` 브랜치로 PR을 생성합니다.
    * PR 제목과 내용을 적절히 작성한 후 'Create pull request' 버튼을 클릭합니다.

## 참여자 명단

이 레포지토리에 Pull Request를 성공적으로 보내신 분들의 명단입니다. 아래 표에 본인의 이름과 GitHub 아이디를 추가해주세요!

| 이름   | GitHub 아이디 |
| ------ | ------------- |
| 김승환 | @tmdghks      |

