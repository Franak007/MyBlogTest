Commande dans le Terminal :

DATABASE_URL="mysql://root:@127.0.0.1:3306/MonProjet"

symfony console doctrine:database:create

git init

git add .

git commit -m "first commit"

git remote add origin https://github.com/Franak007/MyBlogTest.git

git branch -M main

git push -u origin main

symfony console make:entity

symfony console make:migration

symfony console doctrine:migrations:migrate

symfony console make:controller

symfony console debug:router

composer require annotations

symfony console security:hash-password "motsecret"

symfony console make:registration-form

symfony console make:crud