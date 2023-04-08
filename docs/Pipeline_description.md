# Pipeline Description
### orbs
1. install node js
2. install aws elastic beanstalk
3. install aws cli

### jobs
1. Install Front-End Dependencies
2. Install API Dependencies
3. Front-End Lint (lint all frontend application and fix issues)
4. Front-End Build 
5. backend build
6. hold until user approves
7. after that deploy frontend project to s3 bucket and backend project to aws eb

