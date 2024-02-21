## HTTP

### HyperTextTransferProtocol

사실 모든 것이 http로 이루어져있다.

- html,text
- image, 음성, 영상, 파일
- JSON, XML(API)
- 거의 모든 형태의 데이터가 전송 가능

---

### HTTP 특징

- 클라이언트와 서버 구조
- 무상태 프로토콜 (stateless)

  - 서버가 클라이언트 상태를 보존X
  - 예시로 클라이언트가 필요한 데이터를 넘겨준다.
    <br />
    Stateful, stateless 차이
  - 상태유지 -Stateful - 서버가 클라이언트의 이전 상태를 보존 하는 것.
  <div>
  <img src="https://velog.velcdn.com/images/khy226/post/c7693176-11f2-4672-98c1-107d42f2e49e/image.png" width="320">
  <img src="https://velog.velcdn.com/images/khy226/post/bbfc9812-b7de-42a5-a9b5-6db7c0d873e5/image.png" width="320">
  <div>

- 비 연결성 (connectionless)

  - HTTP는 비연결성 특징이 있다. 기본적으로 연결을 유지해야하는 TCP/IP와는 반대의 개념이다. TCP/IP의 경우, 서버 연결이 계속 유지되므로 서버 자원이 소모된다는 단점이 있다. 다시 말해, HTTP는 서버 연결을 유지 하지 않아도 되어, 최소한의 자원을 유지할 수 있다는 장점이 있다.

- HTTP 메시지

요청, 응답, 헤더, 바디
<br />
<img src="https://velog.velcdn.com/images/khy226/post/6823c84c-bea4-48d6-bb3d-3a444a702d14/image.png" width="380">

- HTTP 헤더
  - HTTP 헤더는 HTTP 전송에 필요한 모든 부가 정보를 담기 위해 생성된다. 바디의 내용, 요청정보, 캐시, 브라우저 정보 등
