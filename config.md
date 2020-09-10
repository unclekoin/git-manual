[&#8678; к содержанию](./readme.md)


## git config

Первое, что нужно сделать после установки GIT - указать имя и адрес электронной почты. Сделать это можно глобально:

```bash=
git config --global user.name [ваше имя]
git config --global user.email [email]
```

или для конкретного проекта:

```bash=
git config user.name [ваше имя]
git config user.email [email]
```

Смотрим изменения одним из приведенных ниже способов:

```bash=
git config --list
git config user.name 
git config user.email
cat ~/.gitconfig
```


Чтобы посмотреть все конфигурационные настройки используем команду:

```bash=
git config --list --show-origin
```
