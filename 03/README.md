origin       значит       https://github.com/CheeseCheesson/work-with-github.git

//1
Создать новый фаил touch file.txt
Создать новый проект git init
Добавить фаил git add index.js index.html
Добавить фаил в stage git add .
Закоммитить git commit -m 'my comment'
Просмотреть запись с комментарием git log
Просмотреть запись кратко git log --oneline
Присоединиться к удалённому репозиторию  git remote add origin https://github.com/CheeseCheesson/work-with-github.git
прыгнуть на ветку main - git branch -M main
git push [rep_link] [branch_name]
посмотреть ссылку на репозиторий git remote -v  
Посмотреть назване ветки git branch

//2
удалить ненужный фаил из stage git reset [file.txt]
просмотреть все изменения git diff или для одного файла git diff [file.txt]
уберёт все изменения git reset --hard

//3
.gitignore содержание
build
node_modules
.env