# Assignment 03 장영진

## Service Topic : 제작한 CRUD Frontend Service 주제
도서 관리 프로그램

## Data Fields : 6개 이상의 데이터 Field와 각 항목 설명
1. 도서 ID: 도서의 고유 ID를 부여했습니다.
2. 도서 제목: 도서의 제목입니다.
3. 저자: 도서의 저자입니다.
4. 출판사: 도서의 출판사입니다.
5. 장르: 도서의 장르입니다.
6. 대여상태: 현재 도서가 대여가 가능한 상태인지 아닌 상태인지 나타냅니다.

## List Page : index.html에서 표시한 Field 4개 이상
제목, 저자, 장르, 대여상태

## Validation : add.html과 edit.html에 적용한 Validation 조건 4개 이상
1. 도서 ID 입력
2. 제목 입력
3. 저자 입력
4. 출판사 입력
5. 장르 입력
6. 대여 상태 (대여 가능, 대여중) 선택

## RWD  : Desktop과 Mobile 환경을 어떻게 구성했는지 설명
1. (Mobile) 화면 너비가 768px 이하인 경우 환경에 맡게 font-size, margin을 조정했습니다.
2. (Dektop) 화면 너비가 769px 이상인 경우 마찬가지로 font-size, margin을 조정했습니다.
3. bootstrap의 `container`와 `table-responsive`를 사용하여 화면 크기가 작아져도 콘텐츠가 화면 밖으로 넘어가지 않도록 구성했습니다.

## Bootstrap : 사용한 Bootstrap Component 또는 Class
- `container` : 페이지의 전체 콘텐츠 영역 구성
- `container-fluid` : Navigation 영역 구성
- `navbar` : 상단 Navigation 구성
- `card` : 도서 상세 정보 구성
- `table` : 도서 목록 구성
- `table-responsive` : 모바일 환경에서 Table 대응
- `form-control` : 입력창 구성
- `form-select` : 대여상태 선택창 구성
- `btn` : 버튼 구성
- `btn-primary` : 파란색 버튼 구성
- `btn-secondary` : 회색 버튼 구성
- `btn-danger` : 삭제 버튼 구성
- `badge` : 대여상태 표시
- `d-flex` : Navigation 요소 배치
- `justify-content-between` : Navigation 양쪽 배치

## Problem & Solution : 개발 중 발생한 문제와 해결 방법
처음 mobile 환경을 구성할 때 요소들이 화면 너머로 잘리는 경우가 있었음.
=> AI에게 해결방법을 물어보고 bootstrap의 table-responsive을 사용하면 작은 화면에서도 table 요소들이 잘리지 않고 스크롤 하면 보이도록 해결했습니다.

vercel 베포가 되지 않았음.
=> github의 repo가 private로 되어있어서 나만의 새로운 repo를 만들고 다시 시도하니 해결되었습니다.

## Reflection : 새롭게 알게 된 점 또는 궁금한 점
bootstrap의 사용방법과 여러가지 예시들을 따와서 나만의 페이지를 제작하는 법을 알게 되었습니다.
모바일 환경이나 데스크탑 환경 등 화면이 크고 작을 때에도 각각의 환경에 맞게 구성하는 법을 알게 되었습니다.