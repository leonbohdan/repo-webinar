# repo-webinar

 - Create repo with readme
   - `git clone git@...url`
 - `git init`
   - `git remote add origin git@...url`
 - створення файлу .gitignore (зі списком ігнуруючих файлів)
 - `git add .`
 - `git commit -m 'initial commit'`
 - `git push origin master`

 - `git checkout -b gh-pages`
 - Пишем код
 - `git add .`
 - `git commit -m 'Code for review'`
 - `git push origin gh-pages --set-upstream`

 - Створення **Pull Request** на Github
    - base: `master`
    - compare: `gh-pages`
 - Github -> settings вибір гілки `gh-pages` для публічної сторінки
 - посилання на публічну сторінку додоєте в опис до **Pull Request**
 - посилання на **Pull Request** присилаєте на перевірку


