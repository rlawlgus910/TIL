
git init   #초기화

touch README.md         #파일 만들기

git commit -m "수정사항 이름"      #수정사항 이름?

git branch -M main   #pass?

git remote add origin https://github.com/rlawlgus910/TIL.git

###### 만약 이미 존재한다고 하면
{ git remote remove origin }

git push -u origin master

###### 내용 수정 후
git add .
git commit -m "수정사항 이름"
git push -u origin master
