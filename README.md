# groovy_scripts

This is a Groovy Script for my Jenkins Project.

The link to the article is =>https://medium.com/@daksh.jain00/intelligent-testing-environment-jenkins-groovy-kubernetes-3712d53b7c13

This Groovy code creates 4 Jobs and 1 Build Pipeline:
Job 1 - Pull from GitHub
Job 2 - Launch Kubernetes Pods
Job 3 - Will test the application and also check the desired and current state of Pods. Will also send mails accordingly
Job 4 - Will launch in the final Production Environment and view the page on the Browser

Build Pipeline for 1 single pane view of all the jobs.
