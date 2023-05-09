Інструкція:

Клонуйте репозиторій на локальну машину за допомогою команди:

git clone https://github.com/tkachovua/new-project

Перейдіть до каталогу клонованого сховища

cd new-project

Створіть нову гілку development

git branch development

Перейти до нової гілки development

git checkout development

Надсилайте зміни до віддаленого сховища командою

git push -u origin development

попередньо добавивши змінені файли командою

git add .

та добавивши комміт командою

git commit -m "Повідомлення комміту"
