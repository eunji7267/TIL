# 00_basic_cli

1. `ls` : 목록 조회 (list)

   ```bash
   00_basic_cli.md  a.txt  d.txt  e.txt  images/  markdown.md
   ```

   `ls -al` : 상세 목록 조회

   ```total 28
   drwxr-xr-x 1 최은지 197121    0 12월 29 15:05 ./
   drwxr-xr-x 1 최은지 197121    0 12월 29 14:01 ../
   drwxr-xr-x 1 최은지 197121    0 12월 29 13:42 .git/
   -rw-r--r-- 1 최은지 197121    0 12월 29 15:05 00_basic_cli.md
   -rw-r--r-- 1 최은지 197121    0 12월 29 11:47 a.txt
   -rw-r--r-- 1 최은지 197121    0 12월 29 13:41 d.txt
   -rw-r--r-- 1 최은지 197121    0 12월 29 13:41 e.txt
   drwxr-xr-x 1 최은지 197121    0 12월 29 14:46 images/
   -rw-r--r-- 1 최은지 197121 1345 12월 29 14:47 markdown.md
   ```

   

2. `cd` : 폴더 변경(change directory)
   1. `cd` : `~`폴더(home 폴더)로 이동
   2. `cd 폴더명` : `폴더명`으로 이동
      1. `cd 폴더명/폴더명/폴더명` : 여러개의 폴더 한번에 이동
   3. `cd ..` : 상위 폴더로 이동



3. `mkdir` : 폴더 생성(make directory)
   1. `mkdir 폴더명` : `폴더명`이라는  폴더를 생성
4. `touch` : 파일 생성
   1. `touch A.txt` : `A.txt`파일 생성 ( 빈 파일 )
5. `cp` : 파일/폴더 복사
   1. `cp A B` :`A`라는 파일/폴더를 복사하여 `B`를 생성
6. `mv` : 파일/폴더 이동
   1. `mv A.txt B/A.txt` : `A.txt`파일을 `B`폴더 안으로 이동
   2. `mv A.txt C.txt` : `A.txt`파일 이름을 `C.txt`로 변경
7. `tab` : 자동 완성
8. 방향키 위, 아래 : 명령어 기록(History)