# Система контроля версий Git
- [x] Первоначальная настройка Git
  ```
    git config --global user.name ""
    git config --global user.email ""
  ```
- [X] Просмотр конфигураций удаленных репозиториев
> Список ваших удаленных подключений к другим репозиториям.
  ```
    git remote
  ```
> Аналогично команде выше, но включает URL-адрес каждого подключения.
  ```
    git remote -v
  ```
> Создание нового подключения к удаленному репозиторию.
  ```
    git remote add <name> <url>
  ```
> Удаление подключения к удаленному репозиторию с именем.
  ```
    git remote rm <name>
  ```

- [X] Загрузка репозитория на сайт/локальный сервер
- Локальный
> Добавить все измененные файлы в индекс репозитория
  ```
  git add .
  ```
- Сайт
>Отправка изменений
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

  