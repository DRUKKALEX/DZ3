# Инструкция по работе с командами Git.
Надо установить программы Git (https://git-scm.com/) и VS code (https://code.visualstudio.com/).


Сначала надо создать репозитарий, за которым будет следить Git. Вы создаете папку в корневом каталоге, а в ней файл с расширением .md 

**Очень важно назвать его без пробелов!!!.**

# Основные команды!
* git init  - создается репозитарий - **ОЧЕНЬ ОЧЕНЬ ВАЖНО ЭТО!!!**.
* git add название файла - даете команду на отслеживание программой всех изменений в вашем файле md.
* git commit -m "название изменений" - метка для Вас. Это как точка сохранения.
* __git commit -am__ "" - заменят две последних команды. Создает коммитс(запись) для всех изменений. 
* git reflog - покажет журнал коммитов и их изменений.

* git diff и указать первые четыре сивола двух коммитов - покажет разницу после сохранения коммита.
* git checkout  - переход между коммитами.
# Универсальный "лайфхак"
При выборе новой команды - нажимайте стрелку вверх и Вам будут показаны Ваши предыдущие команды. Это сократит время при наборе новых.
# Работа с удаленными репозиториями. Основные команды.
* git push - направляет Ваш файл на удаленный репозиторий на Github. После этого Ваш файл будет уже в сети.
* git pull - забираем файл к себе с удаленного репозитория. Вы можете прямо на Github свой файл отредактировать и отправить себе не компьютер.

# СПАСИБО)