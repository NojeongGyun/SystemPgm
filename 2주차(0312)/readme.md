<pre>
$ s(super) - 관리자 계정으로 로그인
& sudo(super do) 명령어 - 관리자 계정으로 할 수 있는 명령을 할 수 있음(일반사용자는 하지 못하는 권한 부여)
exit - 관리자 계정이라면 일반 사용자로 돌아감

$ man(mange) -
man 명령어 - 명령어에 대한 상세한 정보를 알려준다.

$ info(information) - 

root - 관리자 계정

$ - 일반 사용자 프롬프트
# - 관리자 프롬프트

apt(Advanced Package Tool) - 패키지를 관리하는 도구(관리자 계정에 로그인 해야지 사용가능)
apt [행동] [패키지명]
ex) sudo apt install gcc (gcc패키지를 관리자 계정을 통하여 다운로드 한다.)

gcc(GNU Compiler Collection) - 컴파일러 모음(컴파일을 사용하는 여러 언어를 실행시켜주는 도구)

. - 현재 디렉토리
.. - 부모 디렉토리
~ - home 디렉토리
/ - root 디렉토리

who - 누가 접속했는지 알 수 있음
whoami - 내가 어떤 계정인지 알 수 있음

ls       : 현재 디렉토리 안의 파일과 폴더 이름을 보여줌
ls -l(long listing)    : 파일의 상세 정보 표시 
ls -al(all + long)   : 숨김 파일까지 상세하게 표시 
ll       : ls -l의 별칭인 줄임말
alias    : 별칭을 하여 각 명령어를 접근 쉽게 만들어줌(SQL의 As와 똑같은 기능임)
</pre>
