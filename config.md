<!--ts-->
* [Git Config](./config.md#git-config)
   * [Мой .gitconfig](./config.md#мой-gitconfig)
   * [Как просмотреть текущие настройки](./config.md#как-просмотреть-текущие-настройки)
<!--te-->


# Git Config

## Мой .gitconfig

Мой .gitconfig лежит [здесь](https://github.com/yuliy/study_git/blob/main/.gitconfig).

На что там стоит обратить внимание:
  * Алиасы: checkout -> co, commit -> ci, status -> st, etc.
  * Просмотр истории коммитов. Дефолтный выхлоп ```git log``` малоинформативен. Удобно пользоваться этими двумя алиасами:
    * ```git lg``` - Отображает прямо дерево коммитов. Очень удобно для понимания, что откуда растёт. Обычно пользуюсь этой командой.
    * ```git plog``` - Просто более компактное линейное отображение истории.

## Как просмотреть текущие настройки
Есть такая команда:
```bash
git config --list
```

Можно также вывести, в каком файле эта настройка установлена:
```bash
git config --list --show-origin
```
