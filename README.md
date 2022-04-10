# Git
git + github 공부

# Git 설치 이후 세팅

1. git --version
2. git init //버전관리 필수
3. git config --global core.autocrlf true  //필수
4. git config --global user.name '이름'    //필수
5. git config --global user.email '이메일' //필수
6. git config --global --list           

1. git init //버전관리 선언                     //필수
2. git status                                  //필수
3. git add . //버전관리 등록                    //필수
4. git status //버전관리할 파일목록             //필수
5. git commit -m 'Start project'              //새로운 버전 만들기와 버전 메세지 필수
6. git log //내역보기                          //필수
7. git branch -M main                         //브랜치 메인
8. git remote add origin 깃헙저장소git파일주소 //원격으로 origin이라는 저장소 추가
9. git push origin master                     //원격의 저장소에 프로젝트 업로드 //필수


주로 쓰는건
1. commit
2. Push
3. Pull

작업을 다하고 commit -> push
다른사람의 작업내역을 받을려면 pull
이것을 생활화해야 문제가 안생긴다.
Github Desktop를 사용하면 간단하게 커밋, 푸쉬, 풀이 가능함.
