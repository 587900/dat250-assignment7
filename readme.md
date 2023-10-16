# DAT250: Assignment 7
By 587900 (Kjetil Berg)

### Description
The instructions of https://github.com/selabhvl/dat250public/blob/master/expassignments/expass7.md were followed to gain experience with RabbitMQ.
Everything went according to the instructions besides what is mentioned under the 'Trials and tribulations' section (problems and noteworthy moments).

### Tools
In this project I installed RabbitMQ 3.12.6 and Erlang/OTP 25.3.2 (Erlang was a dependency of RabbitMQ). The project was completed using Java.

### Running
The instructions described three tutorials from RabbitMQ. For each tutorial, I created two .java files, named HelloWorld*, WorkQueue*, and Topic* accordingly.

### Trials and tribulations
1. All tutorials went without issue, only IntelliJ caused some issues.
2. I created a new IntelliJ project with a "maven archetype". When I created a class and tried running it, I got a "ClassNotFoundException". Though, IntelliJ itself recognized it as a "main file".  
2.1 Deleted the project, created new "empty" instead -> Lead to difficulties defining source directory for build step.  
2.2 Deleted the project, created new project with maven (but not with "maven archetype"). This works as expected.
3. When writing this .md file, I could not open it in IntelliJ (what?)  
3.1 I always make them using https://makeareadme.com anyway. I just copied the results in via notepad instead. I swear IntelliJ worked better before.