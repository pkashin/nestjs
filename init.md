***
### 1. Подготовка к работе
***
- Проверить версию `Nest CLI`
    ```bash
    nest -v
    ```
- Список глобально установленных пакетов `npm`
    ```bash
    npm ls -g
    ```
- Если `Nest CLI` отсутствует в списке, то установить последнюю версию
    ```bash
    npm install -g @nestjs/cli
    ```
***
### 2. Создание стандартного проекта Nest JS
***
- Создание проекта
    ```bash
    nest new [project-name]
    ```
***
### 3. Создание `monorepo` проекта Nest JS
***
- Создать стандартный проект Nest JS
    ```bash
    nest new [project-name]
    ```
- Перейти в директорию проекта
    ```bash
    cd [project-name]
    ```
- Преобразовать в `monorepo` стандартный проект
    ```bash
  nest generate app [my-app]
    ```
  * `[project-name]` - становится проектом по умолчанию
  * `[my-app]` - обычный проект в составе `monorepo`
