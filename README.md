# Git bash Practice 

1. git --version
2. git config --global user.name 사용자이름 
3. git config --global user.email 이메일 
4. cd C:\Users (C드라이브 유저 파일로 이동)
5. mkdir TestRepo (로컬 저장소 폴더 생성)
6. git init (새로운 git 저장소 생성- main 폴더)
7. git add hello.txt (파일 생성)
8. git status로 현재 상태 확인 
9. git commit -m "My New file" (commit 명령어로 변경된 파일이 HEAD에 반영, -m 으로 변경 사항에 대한 메세지 적어둠)
10. git push -u origin main  (원격 저장소에도 반영)
11. 로컬 & 원격 연결하기 
    (1). git remote add origin git@github.com:gabining/git__test.git 
    (2) ssh-keygen -t rsa -C "사용자 이메일"
    (3) cd 로 RSA키가 있는 위치 이동 
    (4) cat / (id_rsa.pub 파일 복사)
    (4) github 홈피의 set ssh에서 add 란에 붙여넣기 
    (5) git push -u origin master (원격저장소에도 변경사항 연결) 
12. git log로 로그 파일 확인 

