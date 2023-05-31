## JAVA 기반 파일 동기화 시스템 🍃


# 요구사항

---

- 다중 클라이언트의 서버 접속/해제 기능
- [x]  1.1 클라이언트의 서버 접속 (또는 로그인)
- [x]  1.2 클라이언트 종료시 서버는 해당 클라이언트 접속 해제 처리
- [x]  1.3 서버는 클라이언트의 접속/해제 정보를 다른 클라이언트들에게 통보
- [x]  1.4 같은 클라이언트 및 여러 클라이언트들의 반복적 서버 접속/해제 테스트

---

- 파일 전송 기능
- [x]  2.1 클라이언트가 전송할 파일 하나 이상 선택
- [x]  2.2 클라이언트가 서버로 선택된 파일들 전송 (파일 업로드)
- [x]  2.3 클라이언트와 서버는 파일 전송 완료 사실 확인 (메시지 출력 등)
- [x]  2.4 클라이언트 접속 상태에서 파일 전송 반복 수행 테스트


---

- 단순 파일 동기화 기능
- [x]  3.1 클라이언트는 파일 업데이트(생성,삭제,수정)를 자동 또는 수동으로 탐지
- [x]  3.2 클라이언트는 파일 업데이트가 서버의 파일과 충돌하지 않음을 확인 (logical
  clock 이용)
- [x]  3.3 클라이언트는 충돌하지 않은 업데이트된 파일을 서버로 전송하여 기존 파일
  덮어씀
- [x]  3.4 삭제된 파일은 서버에서도 삭제

---

- 다른 클라이언트와 파일 단순 공유 기능
- [ ]  4.1 파일 및 공유할 사용자(클라이언트) 선택
- [ ]  4.2 선택 파일을 (서버를 거쳐) 선택한 클라이언트에게 전송
- [ ]  4.3 공유된 파일 업데이트되면 서버뿐만 아니라 공유된 클라이언트에게도 전송
  하여 업데이트


