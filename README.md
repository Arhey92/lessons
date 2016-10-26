# lessons
Repository for some test files

#At start
$ git init 

$ git add .

$ git commit -m "add new files"

$ git remote add origin https://github.com/Arhey92/lessons

$ git push -u origin master

If you take error something like this ('error: failed to push some refs to 'https://github.com/Arhey92/lessons'
                                        hint: Updates were rejected because the remote contains work that you do
                                        hint: not have locally. This is usually caused by another repository pushin             g
                                        hint: to the same ref. You may want to first integrate the remote changes
                                        hint: (e.g., 'git pull ...') before pushing again.
                                        hint: See the 'Note about fast-forwards' in 'git push --help' for details.
')
You should do pull.

$ git pull origin master

$ git push -u origin master

# Example of team work with project
http://prntscr.com/cz2uer

Some info:

https://git-scm.com/book/ru/v1/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D1%8B-Git


Стандартный рабочий процесс с использованием Git'а выглядит примерно так:

1. Вы вносите изменения в файлы в своём рабочем каталоге.
2. Подготавливаете файлы, добавляя их слепки в область подготовленных файлов.
3. Делаете коммит, который берёт подготовленные файлы из индекса и помещает их в каталог Git'а на постоянное хранение.