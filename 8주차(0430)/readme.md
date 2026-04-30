<pre>
명령어 처리기 - Shell

프롬프트에서 ; 를 써서 여러 명령어를 입력 받을 수 있다
ex)date - 서버의 현재 시간입니다.  who - 사용자가 로그인한 시간
  date; who - 두 명령어를 한번에 실행 시킴


chmod +x test1 - test1 파일을 실행할 수 있는 파일로 만듬
./test1 - test1 파일을 실행함

변수 앞에 $를 붙여서 사용함
ex) days=10
    guest=“Katie”     
    echo “$guest checked in $days days ago”  - $guest라는 변수를 사용함
    days=5  
    guest=“Jessica”
    echo “$guest checked in $days days ago”  - $guest라는 변수를 사용함
  

$숫자 
순서대로 오는 인자값을 의미
ex) $0 - argv[0]
    $1 - argv[1]...


 echo $?
return 뒤에 있는 값을 가져 올 수 있음
ex) return 5;

    echo $? - 5출력

=> 활용처는 return 0는 보통 정상적인 경로에서 끝났을 때 사용을 하고, return 0제외 다른 숫자는 정상적으로 끝나지 않았을 때 종료시킨다.
    이 값으로 return 뒤의 숫자를 받아 그 경우에서의 경로를 제공해줄 수 있습니다.

  return 0 -> A 경우로 감
  return 1 -> B 경우로 감



















  
</pre>
