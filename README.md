# H1 Лабораторная работа №3: Основы работы с Git и GitHub.
*В этой работе вы научитесь работать с Git и GitHub.*
# H2 Цели работы:
1. Ознакомиться с основами систем контроля версий Git.
2. Научиться работать с удалёнными репозиториями на GitHub.
3. Научиться использовать ветвление и слияние в Git.
4. Создать и оформить файл README.md для проекта.
**Автор: Ковалевич София, группа ИСП-223а**
echo "# Readme.new" >> README.md
git init
git add README.md
git commit -m "первый коммит"
git branch -M main
git remote add origin https://github.com/Kovalevichs/Readme.new.git
git push -u origin main
