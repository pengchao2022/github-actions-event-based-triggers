# github-actions-event-based-triggers
DevOps demo

- push & pull request triggers for github actions

  - create a new feature branch
  ```sh
  git branch feature/pr_demo
  ```
  - switch to the feature branch
  ```sh
  git checkout feature/pr_demo
  ```
  - add pull_request in github actions cicd
  ```sh
  git commit -am "pr_demo trigger"
  ```
  - push to the feature/pr_demo branch
  ```sh
  git push origin feature/pr_demo
  ```
  
