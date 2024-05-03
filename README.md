# TIL

## 브랜치 정의
1. blah blah

## 브랜치 합치기
- 이슈에 해당하는 작업을 수행할 떄, 별도의 브랜치를 만들고 작업한다
- 작업이 끝난 후에는, pull request를 사용해 내가 작업한 브랜치를 중요 브랜치(`main`, `master`, `development`, `devel`)로 병햡시켜야 한다.

### 명령어
- git merge
- 주의할점: `A`브랜치를 `main`브랜치로 합치려고 할 때는 `main`브랜치를 체크아웃한 상태에서 `git merge A`를 입력한다.