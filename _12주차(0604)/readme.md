#include <stdio.h>
#include <stdlib.h>

int main() {

    printf("=== 시스템 점검 시작 ===\n");

    // 사용자 확인
    system("whoami");

    // 현재 위치 확인
    system("pwd");

    // 시스템 정보
    system("uname -a");

    // 호스트 이름
    system("hostname");

    // 프로세스 ID
    system("echo PID : $$");

    // 메모리 사용량
    system("free -h");

    // 디스크 사용량
    system("df -h");

    // IP 확인
    system("ip addr");

    // 작업 디렉터리 생성
    system("mkdir -p report");

    // 보고서 생성
    system("date > report/system_report.txt");

    // 시스템 정보 저장
    system("uname -a >> report/system_report.txt");

    // 사용자 정보 저장
    system("whoami >> report/system_report.txt");

    // 메모리 정보 저장
    system("free -h >> report/system_report.txt");

    // 디스크 정보 저장
    system("df -h >> report/system_report.txt");

    // 보고서 확인
    system("cat report/system_report.txt");

    // 줄 수 확인
    system("wc report/system_report.txt");

    // 백업 생성
    system("cp report/system_report.txt report/backup.txt");

    // 이름 변경
    system("mv report/backup.txt report/final_report.txt");

    // 권한 변경
    system("chmod 755 report/final_report.txt");

    // 파일 검색
    system("find report -name '*.txt'");

    // 내용 검색
    system("grep Linux report/final_report.txt");

    printf("=== 시스템 점검 완료 ===\n");

    return 0;
}
