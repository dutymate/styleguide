# Git Usage Guide

## Pull request

### Submitting a pull request

모든 리포지토리는 pull request를 기반으로 관리됩니다.

```
$ git clone https://github.com/dutymate/dutymate-v3
$ cd dutymate-v3

# Install packages.
# git checkout -b [NEW_BRANCH]
# (Working...)

$ git commit [...]
$ git push origin [NEW_BRANCH]

# Enroll pull-request!
# in https://github.com/dutymate/dutymate-v3
```

## Commit message rules

좋은 커밋 메시지는 가독성을 높이고 유지보수에도 도움이 됩니다.

### Structure

커밋 메시지는 다음의 형태로 작성해주세요.

```
[#issue] type: Short (50 chars or less) summary of changes
ex. [S12P31A202-1] feat: Summarize changes in around 50 characters or less
```

- 반드시 영어로 작성하고 50자를 넘기지 말아주세요.
- 첫 글자는 대문자로 작성해주세요.
- 문장의 끝에 마침표를 적지 말아주세요.
- 문장을 동사 원형으로 시작하는 명령문 형태로 작성해주세요. (`Added` -> `Add`)

#### Type of changes

| type      | usage |
|:----------| --- |
| feat:     | 새로운 기능 추가 |
| fix:      | 버그 수정 |
| docs:     | 문서 수정 |
| style:    | 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우 |
| refactor: | 코드 리팩터링 |
| test:     | 테스트 코드 작성|
| chore:    | 빌드 업무 수정, 패키지 매니저 수정 |
| revert:   | 풀 리퀘스트 롤백 |
| misc:     | 간단한 수정사항 적용 |

