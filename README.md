# 하이퍼레져 앱 만들기 실습 2일차 - 예제 앱 실행

Hyperledger fabcar 예제

<Mac버전>

1. 터미널(Terminal)을 킨다.

2. fabcar 파일로 이동 (터미널에 명령어 입력) : cd fabric-samples/fabcar/

3. javascript 파일로 이동 (터미널에 명령어 입력) : cd javascript

4. fabcar의 front-end 다운 : https://github.com/saarc/fabric-front-end 로 들어가서 다운 받은 후 해당 폴더를 /Users/Username/fabric-samples/fabcar/javascript 에 폴더를 이동시킨다.

5. 모듈 다운로드 (터미널에 명령어 입력) : npm install

6. 만약 npm install 후 "found 1 critical severity vulnerability run `npm audit fix` to fix them, or `npm audit` for details" 의 메세지가 나오면 해당 명령어를 입력 : npm audit fix

7. 하위 폴더로 이동 (터미널에 명령어 입력) : cd ..

8. network 실행 (터미널에 명령어 입력) : ./startFabric.sh

9. 상위 폴더로 이동 (터미널에 명령어 입력) : cd javascript/

10. Wallet의 Admin 계정 생성 (터미널에 명령어 입력) : node enrollAdmin.js

11. Wallet의 User 계정 생성 (터미널에 명령어 입력) : node registerUser.js

12. 생성된 계정 확인 (터미널에 명령어 입력) : node query.js

13. 현재 위치에 생긴 Wallet 폴더를 상위 폴더로 이동

14. 상위 폴더로 이동 (터미널에 명령어 입력) : cd fabric-front-end

15. 모듈 다운로드 (터미널에 명령어 입력) : npm install

16. 만약 npm install 후 "found 1 critical severity vulnerability run `npm audit fix` to fix them, or `npm audit` for details" 의 메세지가 나오면 해당 명령어를 입력 : npm audit fix

17. 웹페이지 실행 (터미널에 명령어 입력) : node server.js

18. 프론트 페이지 확인 : 웹페이지 주소창에 http://0.0.0.0:8080 입력

주의 ) 프론트 페이지에서 Create a Car 페이지에서 데이터 추가 할떄 CarNo는 CAR0 ~ CAR999 안에서만 입력해야 오류가 발생하지 않는다.
