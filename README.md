# web_git_jenkins_docker

Introduction to continous integration
Continuous delivery is an ongoing DevOps practice of building, testing, and delivering improvements to software code and user environments with the help of automated tools. The key outcome of the continuous delivery (CD) paradigm is code that is always in a deployable state.



In this task we will craete  basically 3 jobs to automate the process.

JOB 1 : Continuous delivery is an ongoing DevOps practice of building, testing, and delivering improvements to software code and user environments with the help of automated tools. if main developer commits the code then it goes to master branch and then jenkins fetches the data form master branch and will launch the production environment on docker.

JOB 2 :  If Developer Commit Code at “development” Branch, Jenkins will automatically fetch the data from the “development” branch and will launch the Testing Environment” on docker with our Web-Application Running.

JOB3 :  If Q&A team approves the features, they run job3 which will merge the “development” branch with “master” branch and again trigger Job1.
