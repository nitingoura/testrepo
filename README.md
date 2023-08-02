# Test assignment

### Section 1 - (Pre-Request)

1. Replace variable from code
    a. << aws account number >>
    b. << aws region >>
2. Add secret to Github to perform github action on push changes to main branch.
    ```
    Doc - https://github.com/aws-actions/amazon-ecr-login
    Secret name - ECR_ACTION_ROLE
    ```
3. create ECR repo and IAM role on AWS console
    ```
    IAM - check doc https://github.com/aws-actions/amazon-ecr-login
    ECR repo - nitin-the-remote-testing
    ```
4. Review Devops ReadMe file under devops folder

### Section 2 - (Folder Descriptions)

1. devops
    a. contains all devops CI/CD related stuff
        1. helm - helm charts for application deployment
2. .github/workflows
    a. cotnains github action definations
3. package
    a. contains application related code


### Section 2 - (Notes)

1. Github action will only perform based on branch and path condition
example:
    ```
    branches:
      - main
    paths:
      - 'package/app/**'
      - ''
    ```
