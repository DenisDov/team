## Навигация
  1. [Создаем аккаунт Google](#add_google_account)
  2. [Регистрируемся в Google Play Console](#register)
  3. [Создаем приложение в Google Play Console](#create_app)
  4. [Заполняем описание приложения](#fill_info)
  5. [Выкладываем apk-файл](#upload_apk)
  6. [Заполняем Возрастные ограничения](#fill_age_limits)
  7. [Заполняем Цены и распространение](#fill_price)
  8. [Публикуем приложение](#publish)
  
<a name="add_google_account"/>

## Создаем аккаунт Google

1. Переходим по ссылке https://accounts.google.com/SignUp
2. Заполняем обязательные поля и нажимаем __Далее__.
3. Читаем и принимаем Политику конфиденциальности и Условия использования.

<a name="register"/>

## Регистрируемся в Google Play Console

1. Переходим в Google Play Console по ссылке https://play.google.com/apps/publish/signup/?hl=ru
2. Выполняем вход с помощью созданного ранее аккаунта Google.

![Регистрация в Google Play Console](images/publish_app/console_sign_up.PNG?raw=true)

3. Чтобы перейти к оплате, читаем и принимаем Соглашение Google Play о распространении программных продуктов.
4. Нажимаем __Оплатить__ и вводим данные карты для оплаты регистрационного взноса ($25).
5. После оплаты заполняем данные аккаунта: имя разработчика, которое будет появляться под названием приложения, адрес электронной почты, веб-сайт и телефон.
6. Нажимаем кнопку __Завершить регистрацию__.

<a name="create_app"/>

## Создаем приложение в Google Play Console

1. Попадаем в Google Play Console после завершения предыдущего шага или переходим по ссылке https://play.google.com/apps/publish/?hl=ru
2. Автоматически открывается раздел Все приложения в боковом меню.
3. Нажимаем кнопку __Новое приложение__.
3. Заполняем язык по умолчанию и название, которое будет отображаться в Google Play.
4. Нажимаем __Создать__.

<a name="fill_info"/>

## Заполняем Описание приложения

![Описание приложения](images/publish_app/console_app_info.PNG?raw=true)

#### Сведения о продукте

- Название, которое будет отображаться для пользователей
- Краткое описание, до 80 символов, отображающееся под названием приложения в списке рекомендованных приложений в Play Market
- Полное описание, отображающееся на странице приложения

#### Графические объекты

Выбираем из папки или перетаскиваем на экран следующие объекты:
- Скриншоты приложения. Не более 8 для каждого типа устройства (телефон, планшетные ПК 7-дюймовый и 10-дюймовый, Android TV, Android Wear). Для публикации приложения необходимо предоставить как минимум 2 скриншота.
- Значок в высоком разрешении - икoнка, отображающийся для приложения в Google Play
- Значок для раздела "Рекомендуемые" - значок, отображающийся в верхней части страницы приложения
- Рекламное изображение используется в ранних версиях Android (до 4.0). Для обновления данных для Google Play оно не требуется.
- Баннер для телевизора требуется для публикации приложения для Android TV.
- Круговая панорама требуется для публикации приложения для Daydream.
- Проморолик. При наличии проморолика кнопка воспроизведения будет накладываться на картинку для раздела "Рекомендуемые" в верхней части экрана.
Ссылка на проморолик указывается в формате https://www.youtube.com/watch?v=yourvideoid

#### Свойства

- Тип приложения. Указываем "Игры" для игр и "Приложения" для всех остальных типов приложений.
- Выбираем подходящую категорию, чтобы пользователи могли найти приложение.

Обязательное поле Возрастные ограничения может быть заполнено только после загрузки apk-файла.

#### Контактная информация, которая будет видна всем на странице приложения

- Веб-сайт
- Электронная почта
- Телефон

#### Политика конфиденциальности

Если у приложения есть доступ к личным данным, то необходимо добавить ссылку на политику конфиденциальности.
В противном случае можно указать "Без политики конфиденциальности".

Для сохранения Описания приложения нажимаем на кнопку __Сохранить проект__ в верхней части страницы.

<a name="upload_apk"/>

## Выкладываем apk-файл

1. В Google Play Console переходим в раздел Версии приложения в боковом меню.
2. Переходим к разделу Управлению рабочей версией.

![Управление рабочей версией](images/publish_app/console_apk_work_version.PNG?raw=true)

3. Нажимаем кнопку __Создать выпуск__.
4. Нажимаем __Не сейчас__ в разделе Google Play App Signing.
5. Нажимаем __Загрузить APK__.
6. Перетаскиваем .apk файл в открывшееся окно или нажимаем __Обзор файлов__ для выбора файла.

<a name="fill_age_limits"/>

## Заполняем Возрастные ограничения

1. В Google Play Console переходим к разделу Возрастные ограничения в боковом меню.

![Возрастные ограничения](images/publish_app/console_age_restrictions.PNG?raw=true)

2. Нажимаем кнопку __Продолжить__.
3. Вводим и подтверждаем адрес электронной почты.
4. Выбираем категорию, соответствующую приложению.
5. Отвечаем на вопросы о приложении - Да или Нет.
6. Нажимаем __Сохранить__ внизу страницы.
7. После сохранения нажимаем __Определить Возрастное ограничение__.
8. После автоматического определения нажимаем кнопку __Установить возрастное ограничение__ в нижней части страницы.

<a name="fill_price"/>

## Заполняем Цены и распространение

1. В Google Play Console переходим к разделу Цены и распространение в боковом меню.

![Цены и распространение](images/publish_app/console_prices.PNG?raw=true)

2. В списке стран устанавливаем галочку __Доступно__ для стран, жители которых смогут скачать приложение. При распространении приложения в России, устанавливаем галочку только для России.
3. Поле Для детей можно не заполнять.
4. В поле Есть реклама устанавливаем значение Да или Нет в зависимости от наличия рекламы в приложении.
5. Переходим в нижнюю часть страницы к разделу Требуется ваше подтверждение.
6. Читаем и принимаем Требования к контенту.
7. Читаем и принимаем Экспортное законодательство США. Его необходимо принять, так как приложение будет размещено на серверах американской компании Google Inc., и загрузка приложения с этих серверов считается экспортом из США.
8. Нажимаем __Сохранить проект__ в верхней части страницы.

<a name="publish"/>

## Публикуем приложение

1. В Google Play Console переходим в раздел Версии приложения в боковом меню.
2. Нажимаем на кнопку __Изменить версию__ в разделе Рабочая версия.
3. Внизу страницы нажимаем кнопку __Просмотреть__.
4. Внизу страницы нажимаем __Опубликовать рабочую версию__. 

Если кнопка __Опубликовать рабочую версию__ недоступна, то можно нажать кнопку __Почему запрещена публикация?__ в верхней части страницы. В появившемся окне отобразится список незаполненных данных.

5. Подтверждаем публикацию приложения.
После подтверждения статус поменяется на Готовится к публикации.