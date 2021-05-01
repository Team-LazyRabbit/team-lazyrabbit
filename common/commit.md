# Commit Message Convention

## 개요
> Witch 프로젝트의 커밋메시지 컨벤션은 아래의 udacity 를 기반으로 진행됩니다.
[👉 Udacity commit style guide](https://udacity.github.io/git-styleguide/)

## 커밋 메시지 구조
- 기본적으로 아래와 같이 `제목/본문/꼬리말` 로 구성.
```
type : subject

body

footer
```

## Commit Type
- `feat` : 새로운 기능 추가
- `fix` : 버그 수정
- `docs` : 문서 수정
- `style` : 코드 포맷팅 등 간단한 포맷 수정
- `refactor` : 코드 리팩토링
- `test` : 테스트 코드, 리팩토링 테스트 코드 추가
- `chore` : 빌드/패키지 등 간단한 수정들이 진행되는 커밋

## Subject
- 제목은 50자를 넘기지 않고, 대문자로 작성
- 마침표를 붙이지 않음
- 과거 시제를 사용하지 않고 명령어로 작성함 
   (해당 부분은 영어커밋을 사용하지 않을 예정이므로 무시해도 된다.)
    - `Fixed` -> `Fix`
    - `Added` -> `Add`

## Body
- 해당 부분은 선택사항이며 모든 커밋에 본문을 붙일 필요는 없음.
- 부연설명 혹은 커밋의 이유를 설명할 필요가 있을 경우 작성함.
- 72자를 넘기지 않도록하며, 제목과 구별을 위해 한 칸 띄워 작성함.

## Footer
- 해당 부분도 Body 와 마찬가지로 선택사항.
- Github issue 및 PR 관련 id 를 작성할 때 사용.
