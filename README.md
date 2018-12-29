# develop_with_tykimos
블록과 함께하는 파이썬 딥러닝 케라스

******************************************************************
gitlab 사용법
******************************************************************

git add .
git commit -m "add total py"
git push -u origin master
tochiro/haha6531
Command line instructions

Git global setup
git config --global user.name "Dongsik Lee"
git config --global user.email "dongsik@hanwha.com"

Create a new repository
git clone http://rnd.hsnc.co.kr/gitlab/DEV/shared/dongsik.datalab.shared.git
cd dongsik.datalab.shared
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

Existing folder
cd existing_folder
git init
git remote add origin http://rnd.hsnc.co.kr/gitlab/DEV/shared/dongsik.datalab.shared.git
git add .
git commit -m "Initial commit"
git push -u origin master

Existing Git repository
cd existing_repo
git remote add origin http://rnd.hsnc.co.kr/gitlab/DEV/shared/dongsik.datalab.shared.git
git push -u origin --all
git push -u origin --tags