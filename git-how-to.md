Cоздала ssh-ключ: ssh-keygen -t ed25519 -С "почта", затем несколько энтеров до картинки. переименовываем файлы. Заходим на гитхаб по ссылке https://github.com/settings/keys.
Затем добавила публичный ключ в свой аккаунт на GitHub: 
Добавление ключа в агент: eval "$(ssh-agent -s)"
ssh-add ~/.ssh/key
Добавить приватный ключ в ssh-agent
Клонировала свой новый репозиторий на рабочий компьютер: git clone git@github.com:ShibinaPS/Shibina.git
Добавила в репозиторий файл git-how-to.md
проверить статус репозитория: git status
подготовить новый файл для комита: git add git-how-to.md
проверить статус репозитория: git status
сделать комит: git commit -m “initial commit”
отправить изменения на сервер: git push