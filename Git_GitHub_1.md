# Git/GitHub 사용법

## Git?

> 분산형 버전 관리 시스템

## GitHub?

> Git 공유 시스템

## Git cli 명령어

1. ls
   > list 전체 목록 출력
2. touch
   > 파일 생성
3. mkdir
   > 폴더 생성
4. rm
   > 파일 삭제
5. cd
   > 폴더 이동
   ```
   cd ..      상위 폴더 이동
   ```

## Git 버전 관리 명령어

1. git init
   > 작업할 메인 폴더 설정
2. git add
   > commit 전 대기 상태에 추가
   ```
   git add .   모든 파일을 add
   ```
3. git commit -m '메시지'
   > commit 하고 기록 남김
4. git config --global user
   > 식별자 - GitHub 아이디와 동일하게 하자
   ```
   git config --global user.email "~~~@~~~"
   git config --global user.name "~~"
   ```
5. git log
   > commit 내역을 확인
6. git status
   > 변경점 확인
7. git remote add origin (repository 주소)
   > GitHub 저장소와 연동, 주소는 로그인 후 저장소 만든 후 생기는것을 가져옴
8. git push origin main
   > 연동된 GitHub 저장소에 실제 업데이트
9. git pull (주소),(브랜치 이름)
   > 저장소에서 pc로 다운로드 가능
