# HTTP ERROR CODE



웹 개발을 하면서 가장 많이 보는 화면이 아마도 ERROR 페이지가 아닐까한다.

에러 페이지가 아니여도 back에서 처리가 되지 않을때에는 브라우저의 개발자 모드에서 에러 코드를 본다.



이번에는 가장 많이보는 에러 코드를 정리해 볼까한다.

| code | message                                                      |
| ---- | ------------------------------------------------------------ |
| 200  | 성공                                                         |
| 202  | Accepted, 서버가 클라이언트의 명령을 받음                    |
| 204  | Non Content, 클라이언트의 요구를 처리했으나 전송할 데이터가 없다. |
| 400  | Bad Request, 요청 실패 (문법상 오류가 있어서 서버가 요청을 이해하지 못함) |
| 404  | Not Found, 문서를 찾을 수 없음 (흔히 URL 맵핑이 잘못 되어있을떄) |
| 405  | Method not allowed. 메서드 허용한됨 (POST 요청인데 GET으로 설정이 되었을때) |
| 408  | Request timeout, 요청 시간 지남                              |
| 500  | Internal Server Error, 서버 내부오류 (대부분 Backend의 콘솔을 보면 이유가 나온다) |
| 505  | HTTP Version Not Supported (가끔 보인다.)                    |



이밖에도 엄청 많은 에러 종류가 있는데 

내가 스프링을 공부하면서 봤던 에러는 대부분 위의 9개의 선에서 정리가 된다.



참조 사이트 [Mozilla 사이트](https://developer.mozilla.org/ko/docs/Web/HTTP/Status)