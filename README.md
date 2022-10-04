# Система контроля версий Git
- [x] Setting up git config
  ```
    git config --global user.name ""
    git config --global user.email ""
  ```

- [X] Adding gitignore
  ![.gitignore](https://i.imgur.com/mRHa8oj.png)

- [X] Adding to Repository/Virtual + Commit
- Virtual
    ```
  git add .
  git commit -m ""
    ```
- Repository
    ```
  git remote add origin main
  git push -u origin main
    ```
  
  
- [X] Adding a branch **root**
  ```
    git checkout -b root
  ```
  
- [X] Merging a branch
  ```
    git checkout root
    git merge main
  ```

  