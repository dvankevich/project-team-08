My fork of team project

Папку для пул реквестів називаємо: my-pool-requests.txt

Порядок дій при роботі

0. Налаштувати Node.js
    Завантажити а потім у VScode в терміналі просто написати: "npm i"
    І вже можна запускати сервер

1.  Робимо git pull стягуємо актуальну версію (Робимо це на гілкі main)

2.  Створюємо нову гілку для своєї задачі: git switch -c "branch_name" -
    створення нової гілки з переходом в неї

3.  Робимо роботу

4.  Все перевіряємо

5.  Пушимо зміни:
git add . - зберігаємо зміни в файлах
git commit -m "commit message" - підписуємо збережені зміни в файлах
git push - відправляємо зміни на сайт GitHub

6. Перекидаємо в трелло свою таску, на гітхабі робимо пулреквест і ставимо тімліда ревьюєром і чекаємо на ревью від тім ліда

7. Якщо все ок то видаляємо свою гілку (локально теж не забувайте)

8. Повертаємось в пункт 1 (перед цим заглянути в трелло)


Різне-

Зверніть увагу на шлях до картинки, без крапок попереду <img src="/images/aboutus/img.png" alt="">

Починайте називати класс або картинку з назви вашого файлу-секції приклад
class: catalog-item  choose-title
img: sale-clock1  reviews-fone

Дошка трелло
https://trello.com/invite/b/RzckXxqO/ATTIa38300fc8d0eeebd79fcbad347a69ebe337C739F/watch-charm

Вимоги до проекту
https://docs.google.com/document/d/1x6QWeDRL-KhO1km5csniZrjHLhiCn70tVj3O0_vz_aY/edit

Макет фігма
https://www.figma.com/file/bskxhpmeboUK1NnQIkHTRi/WatchCharm?type=design&node-id=15307-32&mode=design&t=NrKvQC7D0xggWNhp-0

ТЗ
https://docs.google.com/spreadsheets/d/1XM4gPtEVEcWXa60wLNlLlrAB8ujFh8qCM1CvJw6sqs0/edit?usp=sharing






### Список корисних команд для роботи з git

1. git clone - копіює репозиторій (папку з файлами) на комп'ютер
2. git branch "branchName" - створює гілку з назвою "branchName"
3. git checkout "branchName" - переходить на гілку з назвою "branchName"
4. git checkout -b "branchName" - створюємо гілку з назвою "branchName" і
   переходимо на неї

5. git add . - зберігаємо зміни в файлах
6. git commit -m "commit message" - підписуємо збережені зміни в файлах
7. git push - відправляємо зміни на сайт GitHub
8. git pull - отримуємо останні зміни з сайту GitHub
9. git status - показуємо статус проєкту
10. git branch - показуємо список гілок в проєкті
11. git branch -r - показуємо список гілок на сайті GitHub
12. git branch -a - показуємо список гілок на комп'ютері та на сайті GitHub
13. git fetch - отримуємо зміни з сайту GitHub
14. git stash - зберігаємо незбережені зміни в файлах і кладемо їх в буфер
    обміну

15. git stash apply - вставляємо збережені зміни з буфера обміну
16. git merge "branchName" - зливаємо гілку з назвою "branchName" в поточну
    гілку

17. git merge --abort - відміняємо злиття гілок
18. git branch -d branchName - видаляє гілку локально з проєкту
19. git push origin --delete branchName - видаляє гілку з сайту GitHub
20. git diff - показує відрізки рядків між двома версіями файлу (між двома
    комітами)
21. git log - показує історію комітів
22. cd gitTutorial - переходимо в папку gitTutorial

Для того, щоб вийти з режиму перегляду комітів, використовуйте клавішу `q`
(стосується команди №20 і №21).


git switch -c "branch_name" - створення нової гілки з переходом в неї
git switch "branch_name"    - зміна гілки (перехід в іншу гілку)
git branch -d "branch_name" - видалення локальної гілки
git pull                    - стягнути зміни з гітхабу
git merge "branch_name"     - злити зміни з гілки branch_name в поточну гілку в якій знаходитесь.
