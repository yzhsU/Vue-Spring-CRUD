프로젝트명

이 프로젝트는 Spring Java와 MariaDB를 이용하여 서버사이드를 개발하고, Vue.js와 TypeScript를 이용하여 프론트엔드를 개발한 웹 기능 개발 프로젝트입니다.

사용 기술 및 언어

Spring Java
MariaDB
Vue.js
TypeScript

프로젝트 구성

프로젝트는 다음과 같이 구성되어 있습니다.

- backend/
    - pom.xml
    - src/
- frontend/
    - package.json
    - src/
- README.md

backend/: Spring Java로 작성된 서버사이드 코드가 저장된 디렉토리입니다.
frontend/: Vue.js와 TypeScript로 작성된 프론트엔드 코드가 저장된 디렉토리입니다.
README.md: 프로젝트의 기본 정보와 사용 방법이 포함된 Markdown 파일입니다.

설치 및 실행 방법

1. 서버사이드 설치 및 실행
backend/ 디렉토리로 이동합니다.
pom.xml 파일이 있는 디렉토리에서 다음 명령어를 실행하여 빌드합니다.

$ mvn clean package

다음 명령어로 서버를 실행합니다.

$ java -jar target/{jar 파일 이름}.jar

서버가 실행되면 http://localhost:8080으로 접속할 수 있습니다.


2. 프론트엔드 설치 및 실행
frontend/ 디렉토리로 이동합니다.
다음 명령어를 실행하여 필요한 패키지를 설치합니다.

$ npm install

다음 명령어로 개발 서버를 실행합니다.

$ npm run serve

개발 서버가 실행되면 http://localhost:8080으로 접속할 수 있습니다.