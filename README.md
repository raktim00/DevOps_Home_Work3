# The Full procedure of doing this practical you can find in below link :

## “CI/CD pipeline using Git, Jenkins & Kubernetes” by Raktim Midya - https://link.medium.com/lNp8JMM7bab

## Problem Statement :

1. Create a container image that’s has Jenkins installed using Dockerfile Or You can use the Jenkins Server on RHEL 8/7.
2. When we launch this image, it should automatically start the Jenkins service in the container.
3. Create a job chain of job1, job2, job3, and job4 using build pipeline plugin in Jenkins.
4. Job1: Pull the GitHub repo automatically when some developers push the repo to GitHub.
5. Job2 :
- I) By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container to deploy code on top of Kubernetes ( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed )
- II) Expose your pod so that the testing team could perform the testing on the pod.
- III) Make the data to remain persistent (If the server collects some data like logs, other user information ).
- IV) Job 3: Test your app if it is working or not. If the app is not working, then send an email to the developer with error messages and redeploy the application after the code is being edited by the developer.
