# sourceTreePractice
sourceTreePractice

## git 명령어 요약
- clone : 원격 저장소 (github)을 내 컴퓨터에 복사해 온다.
- add : 내 컴퓨터에서 작업한 파일들을 스토리지에 추가
- commit : 스테이지에 올라온 파일들을 가지고 내 컴퓨터에 저장(세이브와 같다)
- push : 커밋들을 원격 저장소에 업로드

- checkout을 이용하면 아주 쉽게 마지막 커밋으로 되돌아갈수 있다.
- sourceTree의 코드뭉치 버리기 기능을 사용하면 변경사항을 되돌릴 수 있다.


# 브렌치 변경하기
- 브렌치란 : 기존 내용을 유지한 채 새로운 내용을 추가하고 싶을때 사용한다.
- 체크아웃 : 특정 브렌치(혹은 커밋)으로 돌아가고 싶을 때 사용.
- 소스트리의 체크아웃: 브렌치 이름을 더블 클릭하는 것만으로 체크아웃 가능

## 병합하기 1

- 헤드 브렌치에 변경사항이 없고
- 병합 대상 브렌치가 헤드로부터 시작된 경우 
- 아주 쉽게 병합 가능 - Fast Forward

# 병합하기 2
- 헤드 브렌치에 추가적인 커밋이 생기는 경우
- 진짜 병합이 필요해 진다.
- 충돌이 안나면 좋은데, 충돌이 나도 겁내지 말자.

# 충돌 해결하기
- 제일 중요한 점 : 겁내지 말아요!

- 내 기분과는 달리 하늘이 푸르르다.

## 커밋 되돌리기

### reset 사용하기

- 장점: 쉬워요.
- 단점1: 커밋이 날아간다
- 단점2: 강제 푸시가 필요하다.