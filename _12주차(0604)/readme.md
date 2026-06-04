#include <stdio.h>
#include <stdlib.h>

int main() {

    printf("===== 시스템 점검 및 보고서 생성 =====\n");

    system("whoami");                     // 1
    system("pwd");                        // 2
    system("hostname");                   // 3
    system("uname -a");                   // 4
    system("date");                       // 5
    system("cal");                        // 6
    system("id");                         // 7
    system("env");                        // 8
    system("uptime");                     // 9
    system("free -h");                    // 10
    system("df -h");                      // 11
    system("du -sh .");                   // 12
    system("ls");                         // 13
    system("ls -l");                      // 14
    system("ps");                         // 15
    system("ps aux");                     // 16
    system("top -b -n 1");                // 17
    system("ip addr");                    // 18
    system("ping -c 1 8.8.8.8");          // 19

    system("mkdir -p report");            // 20

    system("cd report");                  // 21 (실행은 되지만 system마다 별도 쉘)

    system("touch report/report.txt");    // 22

    system("echo 'System Report' > report/report.txt"); // 23

    system("cat report/report.txt");      // 24
    system("head report/report.txt");     // 25
    system("tail report/report.txt");     // 26
    system("wc report/report.txt");       // 27

    system("cp report/report.txt report/backup.txt");   // 28
    system("mv report/backup.txt report/final.txt");    // 29
    system("chmod 755 report/final.txt");               // 30

    printf("\n===== 보고서 생성 완료 =====\n");

    return 0;
}




1. whoami
2. pwd
3. hostname
4. uname -a
5. date
6. cal
7. id
8. env
9. uptime
10. free -h
11. df -h
12. du -sh .
13. ls
14. ls -l
15. ps
16. ps aux
17. top -b -n 1
18. ip addr
19. ping -c 1 8.8.8.8
20. mkdir report
21. cd report
22. touch report.txt
23. echo
24. cat report.txt
25. head report.txt
26. tail report.txt
27. wc report.txt
28. cp report.txt backup.txt
29. mv backup.txt final.txt
30. chmod 755 final.txt

9pdf

