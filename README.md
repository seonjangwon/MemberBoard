# MemberBoard
MemberBoard 제출용

# 작성자 선장원

# 페이지 설명

## index 

회원가입

로그인 

로그아웃

관리자 메뉴 : 'admin'으로 가입을 해야지만 확인가능

로그인 정보 : 로그인 정보를 출력

회원 메뉴 : 마이 페이지 이동

## member 폴더

### signup 
회원가입 아이디 비번 이름 이메일 전화번호 프로필사진 등록 가능

### signin
아이디 비밀번호 입력 후 HttpSession에 해당 회원 DTO 정보 저장

### admin
관리자 페이지
회원 목록 페이지 이동

### findAll
관리자가 아니면 아무것도 안보임

회원 목록 출력 후 회원 삭제 가능

### mypage
내 정보 모두 출력

수정페이지 이동

내 게시글 페이지 이동

### update
비밀번호를 체크해서 맞으면 정보 수정 가능

### myboard
내가 작성한 게시글 출력


## board 폴더

### write
게시글 작성 가능 작성자는 로그인한 id출력

### findAll
모든 게시글 출력

관리자는 모든 게시글 삭제 가능

작성자는 삭제 수정 가능

다른 사용자는 삭제 수정 불가능

### detail
해당 글 내용 출력

관리자는 모든 게시글 삭제 가능

작성자는 삭제 수정 가능

다른 사용자는 삭제 수정 불가능

댓글 출력

댓글 작성시 바로 출력

댓글에 'ㅅㅂ'이 있으면 출력x

댓글 삭제 가능

### update
제목 작성자 내용 사진 출력

제목 내용 사진 수정 가능

