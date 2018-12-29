# develop_with_tykimos
블록과 함께하는 파이썬 딥러닝 케라스


## gitlab 사용법

1. 기본적인 사용
    git add .
    
    git commit -m "add total py"
    
    git push -u origin master
    
    tochiro/haha***1
    
    Command line instructions

2. Git global setup
    git config --global user.name "Dongsik Lee"
    git config --global user.email "dongsik@hanwha.com"

3. Create a new repository
    git clone https://github.com/dongshik/develop_with_tykimos.git
    cd dongsik.datalab.shared
    touch README.md
    git add README.md
    git commit -m "add README"
    git push -u origin master

4. Existing folder
    cd existing_folder
    git init
    git remote add origin https://github.com/dongshik/develop_with_tykimos.git
    git add .
    git commit -m "Initial commit"
    git push -u origin master

5. Existing Git repository
    cd existing_repo
    git remote add origin https://github.com/dongshik/develop_with_tykimos.git
    git push -u origin --all
    git push -u origin --tags