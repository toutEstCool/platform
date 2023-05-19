## Платформа мероприятий и курсов Ogogo Academy :paw_prints:

Для запуска используйте команду:

```bash
Запустить: yarn run dev
Собрать: yarn run build
```

## Описание проекта

Данный проект нацелен на закрепление материала и практики в команде

- [Figma Design](https://figma.com) - тут будет ссылка на макет
- [Chat for developers](https://chat.com) - чат разработчиков

- [Kanban Board](https://github.com/vercel/next.js/) - Kanban доска проекта
---
## Информация по Git-PR
Следуя этим инструкциям, вы получите копию проекта, которая будет запущена на вашем локальном компьютере для целей разработки и тестирования.

#### Предпосылки
Для установки в вашей системе требуется следующее программное обеспечение:
- Node 18.x
- Yarn v5

Введите следующие команды в терминале, чтобы проверить версии вашего узла и npm:

```bash
node -v
yarn -v
```
---
### Доступные скрипты
---
В каталоге проекта вы можете запустить:
```bash
yarn start
```
Запускает приложение в режиме разработки.
Открытый http://localhost:3000 чтобы просмотреть его в вашем браузере.

Страница перезагрузится, когда вы внесете изменения.
Вы также можете увидеть любые ошибки lint в консоли.

### Установка
---
Выполните следующие действия, чтобы запустить среду разработки.

```bash
git clone https://github.com/toutEstCool/platform.git
```
_ИЛИ С ПОМОЩЬЮ SSH_
```bash
  git@github.com:toutEstCool/platform.git
  ```
- Установка node modules
```bash
yarn install
 ```
### Запустить front-end servers
```bash
yarn start
```
---

## Branches

Prefixes for branches
* feature - feature, task, spike
* fix - bugs

A branch name should be named in following format:

`<prefix>/pm-<clickupTaskId>/<brief-task-name>`

Commit messages should be detailed and be descriptive in following format:

- Write commit messages as a sentence
- Make sure one commit does just one thing
- Use present tense for verbs in the commit description
- The description should clearly describe the changes which were done within the code or any other artifacts included into the commit

Pull Requests (PR)
- After receiving 3 approvals, the developer must execute Squash and Merge
- Use a default PR template
- PR name should follow a template `[PM-clickupTaskId]: task-name`