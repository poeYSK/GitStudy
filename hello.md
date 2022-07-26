# hello git

## git 기초 명령어 요약

- clone: 원격 저장소 복사
- add: 스테이지 영역 작업 파일 추가
- commit: 세이브, 스테이지 영역의 파일들을 가지고 커밋(=세이브)를 만들 수 있다.
- push: 원격 저장소에 커밋을 업로드한다.

## 파일 생성 되돌리기

- 특정 파일의 내용을 마지막 커밋으로 돌리고 싶다면 해당 파일 선택 후 '코드 뭉치 버리기' 선택

## Branch 번경하기

- Branch: 기존 내용을 유지한 채 새로운 내용을 추가하고 싶을 때 사용한다.
- Checkout: 특정 Branch(혹은 commit)으로 돌아가고 싶을 때 사용한다.
- Sourcetree의 Checkout: Branch 이름을 더블 클릭하는 것만으로 Checkout 가능하다.

## Merge 1

- Head Branch에 변경사항이 없고 Merge 대상 Branch가 Head로부터 시작된 경우
- 아주 쉽게 Merge 가능 = Fast-forward

## Merge 2

- Head Branch에 추가적인 commit이 생기는 경우 진짜 Merge가 필요해 진다.
- Conflict가 안나면 좋은데, Conflict가 나도 겁내지 말자.

## Confilct

- 중요한 점: 겁내지 않는 것.
