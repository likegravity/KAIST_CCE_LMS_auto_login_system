# 다운받으시고 가장 먼저 할 일.

https://googlechromelabs.github.io/chrome-for-testing/
stable 버전 다운받아서 chromedriver와 바꿔쳐주시길바랍니다 감사합니다.

본인이 chrome beta, dev, canary를 사용하는 변태라면,
chrome://version/가서 본인 버전에 맞게, 선택한후 다운 받으시면 됩니다.

# chrome 아닙니다 _chrome driver_ 다운받으셔야합니다.

# KAIST_CCE_LMS_auto_login_system
KAIST CCE LMS auto login system for KAIST CCE student

깃허브 계정 있는 사람은 별아이콘좀 눌러주세요

+버그나 뭐 필요한거있으면 Issue 올려주시거나 request 올려주세요


1.무슨프로그램인가?
---
KAIST CCE 학생용 LMS 사이트를
컴퓨터가 켜짐과 동시에 자동으로 로그인 하며 꺼지고, 완료창을 띄우는 프로그램이다.


2.설치방법(다 중요하니까 꼼꼼히 읽기)
-----------------
1. release(오른쪽에 있다)에 가서 .zip 파일을 다운받는다
2. 바탕화면에 풀던 어디에 풀던 알아서하셈(지우면 작동안함!!)
3. 파일에 들어가서 id.txt와 pw.txt를 열어서 너의 아이디랑 비밀번호를 입력하면됨
4. 다 저장하고
5. 잘 작동하는지 확인하기 위해 KAIST_LMS_AutoLogin.exe를 실행하고 로그인 완료 창이 뜨는지 확인해보자
6. 확인했으면 다 닫고 다음 (이제 여기서부터 중요하다)
7. KAIST_LMS_AutoLogin.exe 우클릭->속성에서 _바로가기 만들기_ 를 선택하자
8. Win+R 키를 누르고 shell:startup 입력 후 엔터
9. 그곳에 아까 만든 바로가기 파일을 넣기
10. 다 닫으면 드디어 끝난다.

설정이 좀 복잡하지만 어쩔 수 없습니다.
자동화시킬수는 있는데, 자동화시키려면 파일을 이동시키는 코드를 포함해야합니다.
파일이동시키는 코드는 바이러스탐지가 되더라고요.

개발의도
---
맨날 출석하기 귀찮아 원래는 사이트만 자동으로 열게 했는데
이젠 로그인버튼 누르기도 귀찮아서 그냥 컴퓨터 열면 켜지게 만들었습니다
혼자쓰기는 아까워서 공유하려고하는데
쓸사람이 얼마나 될지는 모르겠네요 
