# Git
git + github 공부

# Git 설치 이후 세팅

1. git --version
2. git init //버전관리
3. git config --global core.autocrlf true
4. git config --global user.name ''
5. git config --global user.email '이메일'
6. git config --global --list

1. git init //버전관리 선언
2. git status
3. git add . //버전관리 등록
4. git status //버전관리할 파일목록
5. git commit -m 'Start project' //새로운 버전 만들기와 버전 메세지
6. git log //내역보기
7. git branch -M main //브랜치 메인
8. git remote add origin 깃헙저장소git파일주소 //원격으로 origin이라는 저장소 추가
9. git push origin master //원격의 저장소에 프로젝트 업로드
