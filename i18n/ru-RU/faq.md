## Что такое Genshin Wishes?
Genshin Wishes это бесплатный сайт с [открытым исходным кодом](https://github.com/genshin-wishes) который позволяет сохранять и просматривать молитвы из Genshin Impact не заходя в игру. Он сделан и поддерживается такими людьми как: [Colin Auberger](https://www.linkedin.com/in/colin-auberger/) и [Jimmy Vergerolle](https://vergerolle.fr).

- Делайте резервную копию своих молитв
- Следите за счётчиком гарантов по всем баннерам
- Просматривайте и сортируйте свои молитвы при помощи удобных фильтров
- Смотрите на подробную статистику по вашим молитвам (для тех кто любит графики и диаграммы 🤓)

## Как вы получаете список моих молитв?
Мы просто достаём их из вашей истории молитв. История молитв в Genshin Impact это веб страница, которая отображается в игре, вы можете сами посмотреть её в окне молитв нажав на кнопку история. Единственное что нам нужно, это временный ключ, который выдаёт вам игра. Этот ключ мы запрашиваем у вас при импорте молитв на сайт.

## Как я могу найти этот ключ для импорта моих молитв?

📢 После обновления 2.3 ссылка со страницы "Обратной связи" больше не работает.

### ПК

1) Откройте Genshin Impact на своем ПК
2) Затем перейдите на страницу история Молитв и подождите, пока она загрузится
3) Вернуться к Windows
4) В меню «Пуск» найдите «Powershell» и откройте «Windows Powershell»
5) Затем скопируйте следующий код и вставьте его в окно Powershell
   
   iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/genshin-wishes/genshin-wishes-getlink/main/global.ps1'));

6) Нажмите ENTER, после чего ссылка будет скопирована в буфер обмена
7) Вставьте его в поле в разделе "Настройки"
 
### Android

1) Перейдите на страницу история Молитв в игре
2) Отключите Wi-Fi и мобильные данные
3) Нажмите кнопку обновить в правом верхнем углу
4) Страница должна выдать ошибку и ссылку
5) Скопируйте эту ссылку и вставьте её в специальном поле на Genshin Wishes

### iOS

✳️ Прежде чем использовать этот метод, вам необходимо прочитать наше руководство о том, [как установить и использовать приложение Stream](https://drive.google.com/file/d/14Q_6v60qLPunrpmA9Bf1KlvsKhaRyPzz/view).

1) Откройте Genshin Impact и перейдите на страницу Молитв в игре
2) Пока Genshin Impact все еще открыт, перейдите в приложение Stream и нажмите Sniff Now
3) Вернитесь в Genshin Impact и откройте историю Молитв
4) Когда страница с историей Молитв загрузится, вернитесь в приложение Stream и нажмите Stop sniffing
5) Затем нажмите на Sniff History и выберите первый элемент в списке
6) Коснитесь запроса, начинающегося с «GET https://hk4e-api-os...»
7) Коснитесь вкладки запроса
8) Нажмите на длинный текст начинающегося с «GET /event/gacha_info…»
9) Наконец, нажмите «Copy Url», затем ссылку в поле в разделе "Настройки"



  
   

### Консоли

     ⚠️ Начиная с обновления 2.3 ссылки с банеров перестали работать.

Вы по-прежнему можете [связать свою учетную запись PlayStation с учетной записью miHoYo](https://genshin.hoyoverse.com/ru/news/detail/14051), а затем использовать метод для ПК/Мобильного устройств.




## Это безопасно?
Да. Так как мы сами игроки в Genshin Impact, мы сами очень озабочены о безопасности аккаунтов.
- **Мы не требуем от вас установить что-либо** на ваше устройство
- **Мы не требуем пароль от вашего аккаунта**
- Временный ключ, который мы запрашиваем хранится на **вашем устройстве** а не на наших серверах
- Также он работает только 24 часа, после этого вам необходимо обновить его на нашем сайте
- Этот ключ никаким образом не даёт возможности войти в ваш аккаунт
- Вы можете попросить нас удалить ваш аккаунт и все связанные с ним данные с нашего сайта в любое время
- Мы используем SSL шифрование

## Есть ли риск получить бан за использование этого сайта?
Никак нет. Мы используем те же методы что и сама игра для того, чтобы получать список ваших молитв, так что риска получить бан нет. Мы используем этот метод на своих собственных аккаунтах уже в течении нескольких месяцев. Mihoyo [высказалась о таких инструментах как наш сайт](https://genshin.mihoyo.com/en/news/detail/5763), и как можете видеть, всё что мы делаем абсолютно легально.

## Какие языки вы поддерживаете?
Сайт изначально разрабатывается на Английском и Французском языках, другие языки поддерживаются [помощниками](https://github.com/genshin-wishes/genshin-wishes-i18n/blob/main/CONTRIBUTORS.md) в [этом проекте](https://github.com/genshin-wishes/genshin-wishes-i18n) на github.
