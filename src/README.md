[2020.02.01]
1. 초기 환경 설정
- node-sass, classnames, react-icons libraray set
- Prettier Set
- index.css 수정
- App.js 수정


[2020.02.02]
1. UI 구성
- TodoTemplate
- TodoInsert
- TodoListItem
- TooList

[2020.02.06]
1. App에서 todos 상태 사용
2. 항목 추가 기능 구현
- TodoInsert value 상태 관리
- TodoInsert Todos 배열에 새 객체 추가
- TodoInsert onSubmit Event 설정
3. 지우기 기능 구현
- Remove 함수 filter 이용 id 항목 추출
- TodoItemList 삭제 함수 연결
4. 수정 기능 기현
- Toggle 함수 map 이용 
- TodoItemList 토글 함수 연결

[2020.02.06]
1. 대량의 데이더 랜더링
2. React.memo 적용(컴포넌트 리랜더링 성능 최적화)
3. useState 함수형 업데이트 적용(함수 생성 성능 최적화)