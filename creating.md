[<u><Вернуться к "Содержанию" </u>](./readme.md)

## Создание репозитория на GITHUB
Давайте создадим новый репозиторий для распространения кода нашего проекта. В панели управления справа нажмите кнопку «New repository» или воспользуйтесь кнопкой + на панели инструментов, рядом с вашим именем пользователя как показано на рисунке Выпадающее меню «New repository».
![Выпадающее меню «New repository»](./assets/Шаг%201.jpg)

Это приведёт к открытию формы «New repository»:
![Форма «New repository»](./assets/Шаг%202.png)

Всё, что в действительности нужно сделать, так это указать название проекта, все остальные поля опциональны. Сейчас, просто нажмите кнопку «Create Repository» и ваш новый репозиторий с названием <пользователь>/<имя_проекта> готов.

Так как в репозитории ещё нет кода, GitHub отобразит инструкции о том, как создать совершенно новый репозиторий или подключить существующий Git проект. Здесь мы не будем этого делать, с этой информацией можно ознакомиться [здесь](https://git-scm.com/book/ru/v2/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D1%8B-Git-%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5-Git-%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D1%8F#ch02-git-basics-chapter).

Теперь ваш проект хостится на GitHub и вы можете предоставить ссылку на него любому желающему. Все проекты на GitHub доступны как по HTTP  
`https://github.com/<user>/<project_name>`,  
так по SSH  
`git@github.com:<user>/<project_name>`.  
Git может получать и отправлять изменения по обоим указанным ссылкам, при этом производится контроль доступа на основании учётных данных пользователя, осуществляющего подключение.

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Page Title</title>
    <style>
      /* Whatever that is inside this <style> tag is all styling for your markup / content structure.
      /* The . with the boxed represents that it is a class */
      .boxed {
        background: #F2F2F2;
        color: black;
        border: 3px solid #535353;
        margin: 0px auto;
        width: 456px;
        padding: 10px;
        border-radius: 10px;
      }
    </style>
  </head>
  <body>
    <!-- This is the markup of your box, in simpler terms the content structure. -->
    <div class="boxed">
   Примечание: Обычно, для общедоступного проекта предпочтительнее использовать HTTPS ссылки, так как это не требует наличия GitHub аккаунта для клонирования репозитория. При этом, для использования SSH ссылки у пользователя должен быть GitHub аккаунт и его SSH ключ должен быть добавлен в ваш проект. Так же HTTPS ссылка полностью совпадает с URL адресом, который пользователи могут вставить в браузер для просмотра вашего репозитория.
    </div>
  </body>
</html>

---
[<u>Следующая глава "Основные команды"> </u>](./commands.md)