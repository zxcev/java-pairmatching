# 기능 구현 목록

## 입출력

-[] 1. 모든 크루 데이터를 읽어온다.

## 기능 선택 기능

-[] 1. 기능 선택 목록을 출력한다.
-[] 2. 해당 기능을 실행한다. 잘못된 입력을 받으면 오류 출력한다.

## 페어 매칭 기능

-[] 1. 과정, 레벨, 미션을 입력 받는다.
-[] 2. 매칭 정보가 이미 존재하는 경우, 재매칭 여부를 입력 받는다. 재매칭 하지 않으면 1번으로 돌아간다.
-[] 3. 저장된 크루들을 랜덤으로 섞어서 리스트를 만든 뒤, 앞에서부터 순서대로 2명씩 뽑아서 페어를 매칭한다. 홀수인 경우 마지막 페어는 3인이 된다.
-[] 4. 같은 레벨에서 페어 매칭 이력이 존재하는 경우, 3번을 과정을 반복한다.
-[] 5. 3회 매칭 실패 시, 오류 메세지를 출력한다.
-[] 6. 매칭에 성공한 경우 결과를 출력한 뒤 기능 선택으로 돌아간다.

## 페어 조회 기능

-[] 1. 과정, 레벨, 미션을 입력 받는다.
-[] 2. 매칭 이력이 없는 경우 오류 메세지를 출력한다.
-[] 3. 매칭 이력이 있는 경우, 결과를 출력한 뒤 기능 선택으로 돌아간다.

## 페어 초기화 기능

-[] 1. 페어 매칭 데이터를 모두 초기화 한 이후 기능 선택으로 돌아간다.