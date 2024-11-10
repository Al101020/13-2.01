https://al101020.github.io/13-2.01/
[![Build status](https://ci.appveyor.com/api/projects/status/h91acavfxiobacgh?svg=true)](https://ci.appveyor.com/project/Al101020/13-2-01)


# 13-2.01 Рабочее окружение

# Webpack5

[Руководство по настройке Webpack](https://webpack.js.org/guides/)
[Руководство по настройке GitHub Actions](https://docs.github.com/en/actions/quickstart)

<!-- # Инструкция:
# 1. Скачать репозиторий https://github.com/netology-code/ahj-code/tree/master/env
# 2. Создать новый репозиторий на github
# 3. Скопировать в новый репозиторий все содержимое папки env
# 4. Настроить новый репозиторий. Указать в нём использование GitHub Action для публикации приложения, вместо публикации # из ветки (gh-pages) alt text
# 5. В файле README.md в строке:
# 	 ![CI](https://github.com/<OWNER>/<REPOSITORY>/actions/workflows/web.yml/badge.svg)
# 	 Заменить <OWNER> на ваш ник на github;
# 	 Заменить <REPOSITORY> на название вашего репозитория;
----------------------------------------------------------------------------------------------
# 2024.11.10
# 1. Скачал репозиторий https://github.com/netology-code/ahj-code/tree/master/env
# 2. Создал пустой репозиторий(13-2.01) -> зашёл Setting -> Pages -> в Source выбираю: GitHub Actions -> 
#    -> нажал create your own(создайте свой собственный) -> Commit changes... (создал commit: Create web.yml)->
# 3. В проводнике на папке с проектами(_GitHub_) ПКМ -> Open Git Bash here -> клонирую себе на ПК:
#    git clone https://github.com/Al101020/13-2.01.git -> перехожу в эту папку: cd 13-2.01
# 4. В клонированную папку проекта копирую содержимое скачаного env
# 5. Теперь опять в Git Bash here:
#    Al@Alex MINGW64 /c/_GitHub_/13-2.01 (main)
#    $ git status - и видим куча изменений, изменения загружаем на GitHub в под именем Al101020
# 6. https://ci.appveyor.com/projects -> NEW PROJECT  -> + ADD -> 13-2.01 -> Settings -> Environment -> 
#    -> Add variable -> подставляю значения новой переменной:
#    GITHUB_TOKEN	 |	??????????????????????????????????
#    -> Save -> в проектах нажимаю новую сборку(new build).
# 7. На GitHub иду в свой проект 13-2.01 -> Settings -> Pages: в GitHub Pages появилась ссылка:
#    https://al101020.github.io/13-2.01/
# 8. У себя на ПК в файл READMY.md добавляем ссылку и бэйджик.
# 9. загружаю изменения:
# 	------ в Git Bash Here ------
# 		git status
# 		git add -A
# 		git commit -m "commit-1"
# 		git push
# 	----------------------------
# 	ошибка:
# Al@Alex MINGW64 /c/_GitHub_/13-2.01 (main)
# $ git push
# Enumerating objects: 5, done.
# Counting objects: 100% (5/5), done.
# Delta compression using up to 2 threads
# Compressing objects: 100% (3/3), done.
# Writing objects: 100% (3/3), 1.58 KiB | 807.00 KiB/s, done.
# Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
# remote: Resolving deltas: 100% (1/1), completed with 1 local object.
# remote: error: GH013: Repository rule violations found for refs/heads/main.
# remote:
# remote: - GITHUB PUSH PROTECTION
# remote:   —————————————————————————————————————————
# remote:     Resolve the following violations before pushing again
# remote:
# remote:     - Push cannot contain secrets
# remote:
# remote:
# remote:      (?) Learn how to resolve a blocked push
# remote:      https://docs.github.com/code-security/secret-scanning/working-with-secret-scanning-and-push-protection/working-with-push-protection-from-the-command-line#resolving-a-blocked-push
# remote:
# remote:
# remote:       —— GitHub Personal Access Token ——————————————————————
# remote:        locations:
# remote:          - commit: 07ac801ece06eaeca2067bc72761d7066d75ec4d
# remote:            path: README.md:33
# remote:
# remote:        (?) To push, remove secret from commit(s) or follow this URL to allow the secret.
# remote:        https://github.com/Al101020/13-2.01/security/secret-scanning/unblock-secret/2odmleqivfnrOVIgAGOrY1wu9PJ
# remote:
# remote:
# remote:
# To https://github.com/Al101020/13-2.01.git
#  ! [remote rejected] main -> main (push declined due to repository rule violations)
# error: failed to push some refs to 'https://github.com/Al101020/13-2.01.git'
# 
# -> удалил у себя проект 13-2.01 и снова клонирую на ПК -> меняю READMY.md -> 
# -> и снова загружаю на GitHub
# 
# А проблема была в файле: README.md. -->