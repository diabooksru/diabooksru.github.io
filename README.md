# Loop Docs

Этот репозиторий содержит исходные файлы для сайта [LoopDocs](https://loopkit.github.io/loopdocs).

## Вклад

Чтобы предложить изменения, форкните эту репу, отредактируйте файлы и отправьте свои изменения в виде пул-реквеста.

### Предварительный просмотр изменений
Для предварительного просмотра вашей работы во время редактирования вы должны установить два питоновых пакета, которые используются для создания этого сайта с помощью [MkDocs](http://www.mkdocs.org/). Это `mkdocs` и `mkdocs-bootswatch`.

Обратитесь к разделу [Правильная установка Python](http://docs.python-guide.org/en/latest/starting/installation/) за помощью в установке Python. MkDocs работает с Python 2.7, 3.3-3.6 и pypy.

* Установка питоновых модулей

```bash
$ cd <loopdocs project location>
$ pip install -r requirements.txt
```

* либо установите модули по отдельности
```bash
$ pip install mkdocs<0.17
$ pip install mkdocs-bootswatch==0.4.0
```

* Локально запустите сервер mkdocs.
```bash
$ cd <loopdocs project location>
$ mkdocs serve
```

* Предварительный просмотр документов в браузере. Большинство изменений будут обновляться автоматически по мере редактирования. Изменения конфигурации и навигации потребуют перезапуска сервера mkdocs.
* Дополнительно, вы можете поделиться предварительным просмотром с другими, загрузив их в ветку `gh-pages` вашей репы.
```bash
$ mkdocs gh-deploy
```

## Соглашения

* Используйте изображения для большей ясности, когда это необходимо

### Знаки отличия
[Admonitions](https://python-markdown.github.io/extensions/admonition/) - это расширение маркировки, позволяющее отформатировать блоки для наглядного отображения информации. Типы: note, info, warning, и danger. Вот несколько примеров, как оформить такие пометки:

```markdown
!!! note
    This admonition uses the default title: 'Note'.

!!! info "My Custom Title"
    This admonition is blue and has a custom title.

!!! warning ""
    This admonition is yellow and has no title.
```
