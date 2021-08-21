git init

git config --global user.name 'Oksana Doikova'
git config --global user.email 'oksana.doikova@gmail.com'

git add . /*добавляем файлы*/
git status /*порверили статус*/
git commit -m 'new file' /*закоментировали*/

git branch homework /*создаю новую ветку*/
git checkout homework /*перехожу на новую ветку*/
git add . /*добавляем новые файлы созданные в этой ветке*/
git commit -m 'add new files' /*закоментировали*/

git remote add origin https://github.com/OksanaDoikova/homework.git /*подсоединились к удаленному репозиторию*/
git push -u origin master /*загружаем основную ветку проекта*/