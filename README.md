# webProgrammingProject
웹프로그래밍 개인 프로젝트


## 구현 사항
### 1. 사용자
- 회원가입, 로그인
- 사용자는 본인이 공모전 정보를 등록할 수 있다.
- 관리자는 관리 페이지엣 사용자 목록을 관리 (조회, 삭제, 수정) 할 수 있다.
- (option) facebook 로그인
- (option) 비밀 번호 수정, 회원 정보 수정
- (option) 여러 명의 관리자 계정을 만들 수 있다.

### 2. 공모전 정보 등록 / 관리 
- 기본정보: 이름, 주최사, 분야, 응시대상, 접수기간, 공모요강, 담당자, 연락처
- 기타정보: 참고 사이트를 참조하여 다양한 추가 정보를 적절한 UI를 통해 입력받는다.
- 등록자는 공모전 정보를 수정/삭제할 수 있다.
- (option) 공모전 포스터를 이미지, pdf 등을 등록할 수 있다.


### 3. 공모전 조회
- 공모전의 목록을 조회할 수 있다.
- 공모전의 상세 정보를 조회할 수 있다.
- (option) 댓글 기능: 사용자는 공모전에 대한 댓글을 남길 수 있다.
- (option) 분야별/상태(접수중/마감임박/마감 등)별 공모전 목록을 조회할 수 있다. 
- (option) 검색: 키워드를 통해 공모전을 검색할 수 있다.
- (option) 추천 기능: 공모전 정보, 댓글 등에 추천(좋아요/싫어요)을 할 수 있다.


### 4. 기타
- 반드시 nodejs, expressjs, mongodb를 사용해야 한다.
- 모든 최신 브라우져(Safari, Chrome, Firefox 등)에서 무리 없이 사용할 수 있어야 한다. 
- 과제의 결과물을 웹에서 확인 가능해야 한다. (AWS, Heroku 등을 통해 deploy해야 함) 
- (option) Responsive Design: 모바일 환경에서도 서비스를 확인가능하도록 만든다. 
- (option) Ajax 기술, 혹은 WebSocket 기술을 활용

