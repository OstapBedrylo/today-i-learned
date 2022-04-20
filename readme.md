КОНСПЕКТ ПО JS

I - GIT
 
Качаємо Гіт - система контролю версій (99% охоплення користувачів)
в ній вже є свій термінал Git Bash
Про Гіт можна почитатти https://git-scm.com/book/uk/v2

Зручна навчалка по Гіту: https://learngitbranching.js.org/?locale=uk

Перевіримо чи Git встановлений
git version

Ініціалізація репозиторія
git init
директорія .git
команда git add та git add .
файл .gitignore

Налаштування Git
git config user.name
git config user.email

Базові команди Git
git init
git status
git add
git commit

Основи роботи в командній стрічці:
cd
ls
mv
rm
cp
cat


Для обміну даними з ін користувачами можна використовувати віддалений репозиторій https://github.com, або інший  (ще є 2 поширені Gitlab, Bitbucket).
Навчальні дані брали з https://github.com/eleks-bootcamp

можна юзати будь який інший термінал, або якусь простішу візуальну IDE, наприклад:
- Visual Studio Code https://code.visualstudio.com (для відображення більшої к-сті параметрів можна скачати Git extension pack)
- https://atom.io
- Github Desktop: https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/getting-started-with-github-desktop
- https://www.gitkraken.com/  
  


Щоб перекинути з локального компа на віддалений сервер потрібно 
1. перевірити всі свої посилання на віддалені сервери git remote -v

1а. видалити оріджн який без токена командою git remote remove origin. Загалом GitBash буде працювати без токена зі звичайним оріджн, але інші програми ні.

1б. встановити посилання на віддалений сервер командою git remote add origin https://<токен>@<посилання на ваш репозиторій починаючи github.com>.git

2. закомітити зміни у локальних файлах командою git commit -am "назва коміту"
am - команда яка автоматично робить add і комітить. В ТЕРМІНАЛІ ПОТРІБНО ЦЕ add ПОСТІЙНО РОБИТИ. 

3. передаємо зміни на віддалений сервак в гілку main командою git push origin main

4. щоб локальну гілку main звязати з віддаленою git push -u origin main

Корисні посилання по css і html:

https://caniuse.com/ - перевірка для версій броузерів

https://cssreference.io/

https://htmlreference.io/

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors

https://flexboxfroggy.com/ - властивості позиціонування flex

 https://cssgridgarden.com/ - та саме grid



