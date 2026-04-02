<pre>include와 lib 차이
헤더 파일(.h)이 들어가는 곳, 라이브러리 파일이 들어가는 곳

- 대표적인 버퍼 문제 -
  <code>
  #include <stdio.h>
    int main(){
    char string[20];
    char c;
    scanf("%s", string);
    scanf("%c", &c);
    printf("%s\n", string);
    printf("!!%c!!\n", c);
    return 0;
    }
  </code>

  - scanf("%s", string); 에서 마지막 널문자가 버퍼에 남아 다음 scanf인 scanf("%c", &c)가 영향을 받는다.
  
    
</pre>
