import sys
sys.stdin = open('input.txt', 'r')
#제출 할떄는 위에 것을 주석처리 하거나 제거하고 제출할 것

a = int(input())
 
for h in range(0,a):
    l = list(map(int, input().split()))
    result = sum(l) / 10
    print('#{} {:.0f}'.format(h+1, result))

 # 깃에 등록하는 법
 $ git init 
  - 깃창으로 연결시키는 거 (노란색 디렉토리 옆에 마스터라는 글이 뜸)

 $ touch 
 - 터치는 파일을 만들때 사용

 $ git add .
 - 현재 폴더위치를 스토릿지로 올림

 $ git commit -m '버전이름'
 - 현재 저장할 버전이름을 지정한다

 $ git remote add origin master 주소
 - 저장소(서버)와 내 컴퓨터(클라이언트)를 연결

 $ git remote -v 
 - 연결상태를 확인

 $ git push -u origin master
 - 처음 저장소에 깃을 등록할 떄는 이렇게 저장, 나중에는 git push만 하면 됨

 $ git log --oneline
 - 원라인으로 보면 한줄로 나타남

 ## 깃을 가져올때

$ git clone 주소 .
 - 저장소에서 자료를 가져옴

$ git restore 파일명(깃애드를 하기 전에 파일을 다시 복구시킴))

$ git pull origin master 
 - 이미 이전버전을 갖고 있는 상태에서 저장소에서 최신버전을 가져옴

그리고 박예린 사랑해
