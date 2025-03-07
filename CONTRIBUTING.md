<p align="center">✨Dvurechensky✨</p>

# Руководство по взносам

1. Форк репо
2. Клонировать свой форк
3. Синхронизируйте свой локальный мастер

    3.1.

    ```bash
    git remote add upstream git@github.com:lifeparticle/Markdown-Cheatsheet.git
    ```

    3.2.

    ```bash
    git fetch upstream
    ```

    3.3.

    ```bash
    git branch --set-upstream-to=upstream/main main
    ```

    3.4.

    ```bash
    git pull
    ```

4. Создайте ветку

    ```bash
    git branch issue-2 # use issue_number, replace issue-2 with appropriate branch name
    git checkout issue-2
    ```

5. Запустите lint

    ```shell
    markdownlint-cli2 "**/*.md" --config ./.markdownlint.json
    ```

6. Внесите изменения в свой форк с помощью git push

    ```bash
    git add .
    git commit -m"Write a meaningfull commit message"
    git push
    ```

7. Создайте запрос на выгрузку

    7.1 Используйте url из терминала

    ```bash
    remote: Create a pull request for 'issue-2' on GitHub by visiting:
    remote:      https://github.com/........................
    ```

   7.2 Если у вас возникли проблемы с поиском url

      a) [Markdown-Cheatsheet Pull requests](https://github.com/lifeparticle/Markdown-Cheatsheet/pulls)

      b) Нажмите на кнопку 'New pull request'

      c) Нажмите на ссылку 'compare acorss forks'

      d) Измените головной репозиторий на ваш форк

      e) Измените ветку на вашу ветку

      f) Создайте pull request

8. Повторите

   ```bash
   git checkout master
   git pull
   ```

<p align="center">✨Dvurechensky✨</p>