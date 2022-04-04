# SCA Assessment

### Jenkinsfile Syntax
Using a declarative pipeline, jenkins build undergoes 3 stages

- **Stage Source(git)** pulls the code from the github repo which is connected via github webhook.

- **Stage Build** packages the code pulled from github repo.

- **Stage Deploy** goes to the folder in the aws instance hosting the jenkins server and assesses the python script `program.py`.
