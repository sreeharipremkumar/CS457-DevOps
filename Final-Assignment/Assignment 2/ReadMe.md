# Assignment 2

## Steps:
  - Create 1 Master and 2 Slave instance on Amazon Web Service
  - Install Jenkins and dependencies on Master
  - Configure Jenkins and create 2 slave node within Jenkins
  - Pass the Git repository in the slave node configuration to get the required files from.
  - Slave 1 - Test server (configured with port 1234)      Slave 2 -Production Server (port 80)
  - Configure the node with Dockerfile build/run commands
  - Create a CI/CD pipeline so that production gets changes when the test approves of no errors
  - Use a webhook to get github commit updates onto the test server
  - Everything is complete. If we make change in git repo and commit, it will be retireved and tested in test server, then if no error occurs it is passed to production server


## [LINK TO DOCKERFILE AND WEBSITE CODE](https://github.com/sreeharipremkumar/dev_jenkins)

## Reference
https://www.youtube.com/watch?v=XZm-ENx9l9o
