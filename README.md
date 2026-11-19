# Сайт Vera Estates

Файлы сайта:
- index.html — главная страница
- thanks.html — страница «Спасибо» после отправки заявки
- images/ — фотографии

## Как опубликовать (GitHub + Netlify)

1. Зарегистрируйтесь на github.com (бесплатно).
2. Нажмите «New repository», назовите его vera-estates, нажмите «Create repository».
3. На странице репозитория нажмите «uploading an existing file» и перетащите
   все файлы из этой папки (index.html, thanks.html, README.md и папку images). Нажмите «Commit changes».
4. Зарегистрируйтесь на netlify.com через кнопку «Sign up with GitHub».
5. В Netlify: «Add new site» → «Import an existing project» → GitHub → выберите vera-estates → «Deploy».
   Через минуту сайт откроется по адресу вида vera-estates.netlify.app.
6. Свой домен: в Netlify откройте «Domain management» → «Add a domain», впишите купленный домен
   и следуйте подсказкам (Netlify покажет, какие записи DNS вписать у регистратора домена).
7. Заявки с сайта: в Netlify откройте «Forms» и включите обработку форм (Enable form detection).
   Затем в «Forms» → «Form notifications» добавьте свою почту, чтобы заявки приходили на email.

## Как обновлять

Подключите репозиторий vera-estates к Claude и напишите, что изменить
(например, «добавь новую виллу» с фото и описанием). Claude внесёт правку в GitHub,
и Netlify обновит сайт автоматически через минуту.
