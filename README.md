# DB를 활용한 게시판 기능 구현 과제

---

GitHub repository 

[https://github.com/JoWoonJi/cloudwoon_board/](https://github.com/JoWoonJi/cloudwoon_board/)

링크 [https://github.com/JoWoonJi/cloudwoon_board/](https://github.com/JoWoonJi/cloudwoon_board/)

---

아이디어 정리

- [x]  DB 환경 구축 → xmapp 활용 apache, mysql  / dbconfig.php
- [x]  apache config 활용 호스트 변조해보기
- [x]  웹에디터 활용 - 써머노트 사용법 익히고 세팅 + 부트스트랩cdn
- [x]  글쓰기 폼 코딩 write.html , write.php
- [x]  글쓰기 ajax 전송
- [x]  글등록, 단방향 암호화-해시
- [x]  다중게시판 구현 맛보기
- [x]  글등록 하기 그림 업로드 원리 배우기. base64 , 정규식 활용, img-src 값만 추출
- [x]  글목록 구현하기 list.html
- [x]  글목록 페이징 처리 공부해보기 lib.php
- [x]  글 목록에서 클릭해서 글보기 구현
- [x]  글 보기 스크립트 view.html , 조회수 기능
- [ ]  글 수정 , 삭제, 비밀번호확인, 목록으로 돌아가기
- [ ]  글 검색 기능 추가해보기
- [ ]  SQL인젝션 공격 및 방어.  보안 코딩 공부해서 적용하기
- [ ]  댓글기능 추가하기 등등

---

- 글쓰기 등록 성공시 // 써머노트 웹에디터 활용법 학습 + 부트스트랩cdn

![글쓰기 구현 - 글등록 성공시](https://github.com/JoWoonJi/cloudwoon_board/blob/main/img/%EA%B8%80%EC%93%B0%EA%B8%B0%20%EA%B5%AC%ED%98%84%20-%20%EA%B8%80%EB%93%B1%EB%A1%9D%20%EC%84%B1%EA%B3%B5%EC%8B%9C.jpg)

---

- 글 목록 읽기

![게시글 목록출력,글쓰기 버튼 클릭](https://github.com/JoWoonJi/cloudwoon_board/blob/main/img/%EA%B2%8C%EC%8B%9C%EA%B8%80%20%EB%AA%A9%EB%A1%9D%EC%B6%9C%EB%A0%A5%2C%EA%B8%80%EC%93%B0%EA%B8%B0%20%EB%B2%84%ED%8A%BC%20%ED%81%B4%EB%A6%AD.jpg)

---

- DB 연결, 저장 확인

![DB 연결,저장 구현](https://github.com/JoWoonJi/cloudwoon_board/blob/main/img/DB%20%EC%97%B0%EA%B2%B0%2C%EC%A0%80%EC%9E%A5%20%EA%B5%AC%ED%98%84.jpg)

---

- 게시글 클릭해서 읽기  + 조회수 기능

![게시글 클릭시- 글읽기 구현 -조회수 기능](https://github.com/JoWoonJi/cloudwoon_board/blob/main/img/%EA%B2%8C%EC%8B%9C%EA%B8%80%20%ED%81%B4%EB%A6%AD%EC%8B%9C-%20%EA%B8%80%EC%9D%BD%EA%B8%B0%20%EA%B5%AC%ED%98%84%20-%EC%A1%B0%ED%9A%8C%EC%88%98%20%EA%B8%B0%EB%8A%A5.jpg)
