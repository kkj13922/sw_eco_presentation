1. 로컬에서 임의의 디렉토리 생성
2. 디렉토리를 오른쪽 버튼 클릭하여 git bash here를 하거나, cmd에서 생성된 디렉토리로 move
3. $ git init (현재 디렉토리를 로컬저장소로 만듦)
4. $ git status (add할 파일의 유무 체크, 빨간색이면 그 파일을 add해줘야하고, 초록이면 add됨)
5. $ git add . (모든 파일이면 . , 특정 파일만 업로드하고자 하면 add [파일명])
6. $ git commit -m "[메시지 내용]" (push시 원하는 메시지 등록하고 commit함)
7. $ git remote add origin [repository 주소] (https://github.com/kkj13922/sw_eco_presentation.git)
8. $ git remote -v (7번 8번 과정으로 자기가 만든 로컬저장소와 우리가 쓰는 원격저장소를 연결)
9. $ git push origin master (아까 commit 해두었던 로컬 파일들을 원격저장소에 올림)

-> 한번 로컬저장소를 만들면 status 확인하고 업데이트된 파일들 add하고 commit하고,
이전에 연결해두었던 원격저장소에 push하면 됨
