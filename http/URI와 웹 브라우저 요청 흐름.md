## URI

- URI는 로케이터, 이름 또는 둘다 추가로 분류될 수 있다.
  <br />
  <img src="https://file.notion.so/f/f/aa7a1f30-30ce-4c5d-9580-951ff6ff8376/096908b8-5f84-43b6-b83a-b3adf1938cec/uIRL.png?id=99a14a44-e0ac-4b0f-805a-780601730137&table=block&spaceId=aa7a1f30-30ce-4c5d-9580-951ff6ff8376&expirationTimestamp=1708156800000&signature=FdKmxjsF5h9RhyM4JqAafAbqwbOMmU5uQH_f8Bwj9Do&downloadName=uIRL.png" width="350">

---

## 웹 브라우저의 요청 흐름

<br />
<img src="https://file.notion.so/f/f/aa7a1f30-30ce-4c5d-9580-951ff6ff8376/e45636c8-7353-42c5-ba86-924134bda28c/%E1%84%80%E1%85%AE%E1%84%80%E1%85%B3%E1%86%AF.png?id=26b27c92-983c-4712-b7ad-14e61f8969d7&table=block&spaceId=aa7a1f30-30ce-4c5d-9580-951ff6ff8376&expirationTimestamp=1708156800000&signature=tjIH_B1lhL2a6YyvmFPvKeC8OdBtjmnFXXjbW6UiZgw&downloadName=%E1%84%80%E1%85%AE%E1%84%80%E1%85%B3%E1%86%AF.png" width="420">

1. 웹 브라우저에 URL 요청
2. DNS서버를 통해 IP를 조회한다.
3. 웹이 http 메세지 생성
4. SOCKET라이브러리를 통해 전달
   - TCP/IP 연결
   - 데이터 전달
5. TCP/IP 패킷 생성, HTTP 메세지 포함
6. 요청 패킷을 서버로 전달
7. 서버는 응답에 대한 http 메시지를 만들어 클라이언트에 전달한다.
8. 클라이언트는 전달받은 html을 렌더링한다.
