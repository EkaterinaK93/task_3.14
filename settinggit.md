[<u> :point_left: Вернуться к "Содержанию" </u>](./readme.md)

## Установка Git
#### Как установить Git на любую ОС

Git можно установить на самые распространенные операционные системы, такие как Windows, Mac и Linux. На самом деле, Git устанавливается по умолчанию на большинстве компьютеров Mac и Linux!

#### Проверка Git
Чтобы проверить, установлен ли у вас уже Git, откройте приложение терминала.  
* Если вы используете Mac, найдите приложение командной строки под названием «Терминал»

* Если вы работаете на компьютере с Windows, откройте командную строку Windows или Git Bash.  

Открыв приложение терминала, введите `git --version`. Вывод либо сообщит вам, какая версия Git установлена, либо предупредит вас о том, что это неизвестная команда. Если это неизвестная команда, читайте дальше и узнайте, как установить Git.

#### Установка Git с помощью GitHub Desktop
При установке GitHub Desktop также будет установлена последняя версия Git, если она у вас еще не установлена. С GitHub Desktop вы получаете версию Git для командной строки с надежным графическим интерфейсом. Независимо от того, установлен ли у вас Git или нет, GitHub Desktop предлагает простое средство совместной работы для Git. Подробнее можно узнать [здесь](https://desktop.github.com/).

#### Установка Git в Windows
1. Перейдите к последней [версии установщика Git для Windows](https://gitforwindows.org/) и загрузите последнюю версию.

2. После запуска установщика следуйте инструкциям на экране мастера установки Git, пока установка не будет завершена.

3. Откройте командную строку Windows (или Git Bash, если вы решили не использовать стандартную командную строку Git Windows во время установки Git).

4. Введите для проверки того, что Git установлен `git --version`

Примечание: [git-scm](https://git-scm.com/download/win) является популярным и рекомендуемым ресурсом для загрузки Git для Windows. Преимуществом является то, что загрузка автоматически начинается с последней версии Git.

#### Установка Git на Mac
На большинстве версий MacOS Git уже установлен, и вы можете активировать их через терминал. Однако, если по какой-либо причине у вас не установлен Git, вы можете установить последнюю версию Git одним из нескольких популярных способов, перечисленных ниже:

###### Установка Git из установщика
1. Перейдите к последней [версии установщика Git для macOS](https://sourceforge.net/projects/git-osx-installer/postdownload) и загрузите последнюю версию.

2. После запуска установщика следуйте приведенным инструкциям до завершения установки.

3. Откройте командную строку «терминал» и введите, чтобы убедиться, что Git установлен.git version

###### Установка Git из Homebrew
***Homebrew*** — популярный менеджер пакетов для macOS. Если у вас уже установлен Homwbrew, вы можете выполнить следующие действия, чтобы установить Git:
1. Откройте окно терминала и установите Git с помощью следующей команды: `brew install git`
2. После завершения вывода команды вы можете проверить установку, введя: `git --version`

#### Установка Git в Linux

Вы можете установить Git с помощью инструмента управления пакетами, который поставляется с вашим дистрибутивом.

###### Debian/Ubuntu
1. Пакеты Git доступны с помощью apt

2. Рекомендуется убедиться, что вы используете последнюю версию. Для этого перейдите в оболочку командной строки и выполните следующую команду, чтобы убедиться, что все обновлено:  
`sudo apt-get update`

3. Чтобы установить Git, выполните следующую команду:  
`sudo apt-get install git-all`

4. После завершения вывода команды вы можете проверить установку, введя: `git --version`

###### Fedora
1. Пакеты Git доступны с помощью .dnf
2. Чтобы установить Git, перейдите в командную строку и выполните следующую команду:  
`sudo dnf install git-all`
3. После завершения вывода команды вы можете проверить установку, введя: `git --version`

Примечание: Вы можете скачать соответствующие версии Git и узнать больше о том, как установить Git на определенные системы Linux, например, установить Git на Ubuntu или Fedora, [в документации git-scm](https://git-scm.com/download/linux).

#### Другие способы установки Git
Хотите установить Git через исходный код? Подробнее смотрите [здесь](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

---
[<u>Следующая глава "Терминология" :point_right: </u>](./term.md)