# ssi-devops
develop

        1. create branch develop 
        git checkout -b develop
        2. add readme
        git add .       
        3. commit changes 
        git commit -m "develop"
        4. push changes
        git push origin develop
        
feature

        1. create branch feature 
        git checkout -b feature
        2. update branch
        git pull origin develop
        3. add readme
        git add .       
        4. commit changes 
        git commit -m "feature"
        5. push changes
        git push origin feature                          
        
hotfix

        1. create branch hotfix 
        git checkout -b hotfix
        2. update branch
        git pull origin feature
        3. add readme
        git add .       
        4. commit changes 
        git commit -m "hotfix"
        5. push changes
        git push origin hotfix
        
release

        1. create branch release 
        git checkout -b release
        2. update branch
        git pull origin hotfix
        3. add readme
        git add .       
        4. commit changes 
        git commit -m "release"
        5. push changes
        git push origin release
        
        
update master 

        1. update master with release
        git checkout master
        2. pull from release
        git pull origin release
        3. add readme
        git add .       
        4. commit changes 
        git commit -m "master"
        5. push changes
        git push origin master 