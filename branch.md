[&#8678; к содержанию](./readme.md)

## git branch

Команда **git branch *[назавание ветки]*** - создает новую ветку.

```bash=
git branch new-branch # создаем новую ветку
git branch            # смотрим где мы находимся

* master
  new-branch

git checkout new-branch # переключаемся на новую ветку

Switched to branch 'new-brunch'

git branch

  master
* new-branch

git checkout -b branch-name # создаем ветку и автоматически переключится на неё
```

```bash=
git push origin branch-name # отправляем созданную ветку на сервер

git checkout origin/branch-name -b branch-name # получить ветку с удаленного репозитория
```

Смотрим все существующие ветки:

```bash=
git branch # локальные
git branch -r # на сервере
```
Переключаемся на ветку:

```bash=
git checkout branch-name
```

### Ссылки

* [Ветвление в Git - Основы ветвления и слияния](https://git-scm.com/book/ru/v2/%D0%92%D0%B5%D1%82%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B2-Git-%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D1%8B-%D0%B2%D0%B5%D1%82%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B8-%D1%81%D0%BB%D0%B8%D1%8F%D0%BD%D0%B8%D1%8F)
* [Ветки в Git на Hexlet](https://ru.hexlet.io/courses/intro_to_git/lessons/git-branching/theory_unit)