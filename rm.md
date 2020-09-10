[&#8678; к содержанию](./readme.md)

## git rm

Команда **git rm *[опции]*** - удаляет файлы из репозитория и  индекса.

Удаление файла из коммита и проекта:

```bash=
git rm file-name
git commit --amend --no-edit
```

Удаление файла из коммита, но не удаляя из проекта:

```bash=
git rm --cached file-name
git commit --amend --no-edit
```

* [Подробнее](https://git-scm.com/docs/git-rm)
