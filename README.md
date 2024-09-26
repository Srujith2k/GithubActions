# GithubActions
Just testing Github Actions
This project is cloned from 
https://github.com/nanuchi/my-project.git
For learning purpose

##### build the project
    ./gradlew build

##### build Docker image called java-app. Execute from root
    docker build -t java-app .
    
##### push image to repo 
    docker tag java-app demo-app:java-1.0