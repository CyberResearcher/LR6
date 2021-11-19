# Лабораторная работа №6
- **Создан аккаунт на сайте GitHuib**

*https://github.com/CyberResearcher*

- **Создана копия репозитория (Fork) в личное хранилище**

*https://github.com/CyberResearcher/LR6*

- **Установлен и настроен Git**

С помощью команд `git config --global user.name <username>` и `git config --global user.name <username>`
вводим имя пользователя и email

![git config](screenshots/git-config.png)

- **Клонирование удаленного репозитория на копьютер с помощью команды** `git clone <url>`

![git clone](screenshots/git-clone.png)

- **Добавление файла** *Added-file* **через интерфейс GitHub и запрос его для локального репозитория командой** `git pull`

![Added file](screenshots/Added-file.png)

![git pull](screenshots/git-pull.png)


### Локальная работа

- **Получение истории операций для каждой из веток командами ** `git log` ** для отчета и ** `git checkout <branch>` * для переключения веток*

![git log master](screenshots/git-log-master.png)

![git log branch1](screenshots/git-checkout-branch1.png)

- **Попытка слияния веток**

Для исправления конфликта вручную открываем файл mergefile.txt блокнотом командой `notepad mergefile.txt` и корректируем текст

![git merge error](screenshots/git-merge-err.png)

![git merge correct](screenshots/git-merge-correct.png)

Теперь индексируем и коммитим исправленный файл командами `git add <file>` и `git commit -m <commit name>`

![git commit merge](screenshots/git-commit-merge.png)

- **Удаление побочной ветки**

Удаляем побочную ветку из локального и удаленного репозитория командами `git branch -d <branch>` и `git push <url> --delete <branch>` соответственно 

![delete branch1](screenshots/delete-branch1.png)

- **Несколько важных изменений**

![important changes](screenshots/2-Changes.png)

- **Хард откат ~~важного~~ коммита**

Хард ресет коммита производим командой `git reset --hard <commit>`

![hard reset](screenshots/hard-reset.png)

- **Создание ветки для отчета**

Создаем и сразу переключаемся на ветку отчета командой `git checkout -b report`

![report branch](screenshots/creation-report-branch.png)

### Отчет

История изменений в форматированном виде с помощью команды `git log --pretty=format:"%C(yellow) %h %Cgreen %as %Cred %an %Creset %s"`

![final report](screenshots/final-report.png)