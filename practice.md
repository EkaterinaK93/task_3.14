[<u> :point_left: Вернуться к "Содержанию" </u>](./readme.md)

## Практическое задание 
#### Цели
Научиться создавать Git-репозиторий с нуля.
#### Создайте страницу «Hello, World»
Начните работу в пустой директории (например, work), затем войдите в неё и создайте там файл `hello.html` с таким содержанием:

Выполните:  
`mkdir work`  
`cd work`  
`touch hello.html`

Файл: hello.html
`Hello, World`

#### Создайте репозиторий
Теперь у вас есть директория с одним файлом. Чтобы создать Git-репозиторий из этой директории, выполните команду `git init`.

Выполните:  
`git init`

Результат:  
`Initialized empty Git repository in /home/alex/githowto/repositories/work/.git/`

#### Добавьте страницу в репозиторий
Теперь давайте добавим в репозиторий страницу «Hello, World».

Выполните:  
`git add hello.html`  
`git commit -m "Initial Commit"`

Результат:  
`$ git add hello.html `  
`$ git commit -m "Initial commit" `  
`[main (root-commit) 5836970] Initial commit `  
`1 file changed, 1 insertion(+)`  
`create mode 100644 hello.html`

---
[<u>Следующая глава "Полезные материалы" :point_right: </u>](./materials.md)