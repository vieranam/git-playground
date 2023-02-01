**4. 데이터 수집 성공 여부 알람 기능 설정
  - 데이터 수집 성공, 실패 관련 정보를 로그로 기록하고 해당 로그를 압축해서 이메일로 전송하는 기능을 제공하기에 사용자는 선택적으로 사용할 수 있습니다.
  - 해당 기능을 사용하기 위해선 SendEmailFlow 프로세스 그룹을 실행해야 합니다.
  - 그 전에 SendEmailFlow의 putEmail 프로세서의 아래 속성값을 설정해야 합니다.
  - SMTP Username: SMTP 계정의 이메일 주소 ex) xxx@gmail.com
  - SMTP Password: SMTP 계정의 비밀번호 ex) 1234
  - From: 보내는 계정의 이메일 주소 ex) xxx@gmail.com
  - To: 받는 이메일 주소 ex) yyy@gmail.com
  - 속성값을 다 입력했다면, SendEmailFlow 프로세서 그룹을 실행합니다.
