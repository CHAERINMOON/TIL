# TIL
Today I Learned

Git이란?
버전 관리 시스템 (VCS, Version Control System)

코드 변경 이력 추적, 협업 도구로 사용

로컬 저장소 + 원격 저장소(GitHub 등)로 구성


1. Git 기본 명령어

 `git init`             새 Git 저장소 초기화 
 `git clone [URL]`      원격 저장소 복제     
 `git status`           변경 사항 확인      
 `git add [파일명]`        변경된 파일 스테이징   
 `git add .`            모든 변경 파일 스테이징 
 `git commit -m "메시지"`  커밋(버전 기록 남김)  
 `git log`              커밋 로그 확인      
 `git diff`             변경된 내용 비교     
 `git restore [파일명]`    변경 전으로 되돌리기   
 `git reset`            스테이징 취소       


2. Git 브랜치

 `git branch`            브랜치 목록 확인         
 `git branch [브랜치명]`     새 브랜치 생성          
 `git checkout [브랜치명]`   브랜치 이동            
 `git switch [브랜치명]`     브랜치 이동 (새 명령어)    
 `git merge [브랜치명]`      현재 브랜치에 다른 브랜치 병합 
 `git branch -d [브랜치명]`  브랜치 삭제            


3. Github 연동

 `git remote add origin [URL]`  원격 저장소 연결           
 `git remote -v`               원격 저장소 확인           
 `git push -u origin main`     원격 저장소에 업로드 (처음)    
 `git push`                    변경 사항 푸시            
 `git pull`                    원격 저장소에서 최신 코드 가져오기 


4. Git 설정

 `git config --global user.name "이름"`    사용자 이름 설정  
 `git config --global user.email "이메일"`  사용자 이메일 설정 
 `git config --list`                     현재 설정 확인   
