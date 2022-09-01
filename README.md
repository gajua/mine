# -git clone은 리모트 설정을 자동으로 해주는 초기 다운로드에 사용하고 git pull은 리모트 설정이 이미 되어있을 떄 
업데이트 사항 등을 다운로드 할 떄 사용한다고 합니다

코드로 치는 것 = CLI

클릭으로 하는 것 = GUI

로 보시면 됩니당


GUI 그래픽 유저 인터페이스 (클릭 클릭 클릭~)
CLI 커맨드 라인 인터페이스 - 코드로 치는것 (오늘 배운 터미널 입력)


터미널 입력키
$ ls

$ mkdir sewon		#폴더 생성

$ cd ..			#상위 폴더 이동

$ cd test 		#test 폴더 이동

$ cd sewon		# 

$ touch test.html  		#test.html 파일생성

$ vi test.html		#실무에서는 vim을 사용.

i

ESC

;wq!

$ cat test.html

$ cd ..

$ rmdir sewon

-----

$ git config --global user.name "sewon.kim"

$ git config --global user.email sewon0325@naver.com

$ git config --list

$ git init

$ ls -al

$ touch README.md

$ git status

$ git add .

$ git commit -m 'first commit'

수정하고

$ git add .

$ git commit -m second commit'

수정하고

$ git add .

$ git commit -m 'third commit'

$ touch .gitignore

-> 텍스트에 숨기고싶은 파일이름 입력 후 저장(004.html , *.html)

$ git status

----
