# KB손해보험 대표 홈페이지 인터넷 회원 로그인 테스트

## 테스트 목적

로그인 기능이 정상적으로 동작하는지 확인한다.

## 테스트 범위

- 정상 로그인
- 아이디 오류
- 비밀번호 오류
- 빈 값 입력
- 아이디 길이 초과
- 비밀번호 공백 입력
- 로그아웃

## 테스트 결과 요약

| TC-ID | 결과 |
|--------|--------|
| TC-LOGIN-01 | PASS |
| TC-LOGIN-02 | FAIL |
| TC-LOGIN-03 | FAIL |
| TC-LOGIN-04 | FAIL |
| TC-LOGIN-05 | FAIL |
| TC-LOGIN-06 | PASS |
| TC-LOGIN-07 | FAIL |
| TC-LOGIN-08 | PASS |
| TC-LOGIN-09 | PASS |
| TC-LOGIN-10 | PASS |

## 발견 사항

### TC-LOGIN-03

비밀번호 오류 입력 시 예상한 오류 메시지가 아닌 다른 메시지가 노출됨.

향후 버그 리포트 작성 대상으로 분류.

## 작성일

2025-07-01