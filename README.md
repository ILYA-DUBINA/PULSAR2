1. git status
2. git add [files], allfiles -> . - добовляет файлы в stage
   3 git commit -m "commet"
   4 git log / git log --oneline // краткая информация и просто информация
   5 git push [rep_link] [branch_name]

   Затем, если вы внесли изменения в ветку «из прошлого» и хотите снова запушить, вам придется использовать force push.
   Внимание: force push — штука опасная, использовать ее можно только в крайнем случае, когда других вариантов не остается. Force push перепишет историю вашего приложения — все, что было после force push, исчезнет.
   git push -f origin master

   git config (user.name user.email) - отображение имени и адреса НУЖНО ПРОВЕРЯТЬ ВСЕГДА

   git pull origin branchname --allow-unrelated-histories - связывает не связанные папки(репозитории)
   git remote -v - просмотр папки привязана ли она к какому то репозиторию на github
   git remote add origin [url папки репозитория] - привязка нашей папки к папке репозитория на github
   git push origin(git remote -v) master(git branch)
   git reset - удаляет подготовленый файл со stage
   git diff / diff [file] - просмотр изменных строчек в файлах
   git reset --hard - возвращает изменения прошлые в начальную позицию
   git pull [rep_link] [branch_name] - перемещает ветку из локального редактора кода на глобальный наш сайт

   git branch [name] - создание ветки и просмотр всех веток
   git cheсkout [name] - переход на другую ветку
   git merge [name_branch] - слияние веток через терминал
   git branch -d [name_branch] - удаление ветки в терминале редактора кода(локально) и глабально в github (отдельно удаляется)
   git branch -b [name_branch] - создает новую ветку и сразу переключается на нее
