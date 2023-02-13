# GitHub Actions Examples

Thie repository contains GitHub Actions workflows to automate various DevOps Tasks. 

## [Auto Generate Pull Request Commit message](.github/workflows/auto-pr-comment.yaml)

  - This GitHub Action will create commit message in below format and add it as comment in Pull Request 
  ```
  Note: Please ensure to copy-paste the below message while merging this pull request. Failing to do this will block the pull request merge operation

  Title: 
  Files Modified:
  Source Branch : 
  Author: 
  Assignee: 
  Reviewers: 
  ```
  
  - All the values will be auto-populated from the Pull Request. Field will be kept blank if value is not available. Developer can append any additional fields while merging Pull rquest. 
  -  Example - https://github.com/shailesh-vaidya/github-actions-examples/pull/32#issuecomment-1422517246 
  

  
