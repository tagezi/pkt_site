# pkt_site
Адаптация движка и разработка плагинов клубного сайта для ММСОО "Петроградский Клуб Туристов"

## Лицензия
Весь вклад в проект вносится под свободной лицензией GPL v2. Лицензия выбрана для совместимости с проектом движка и его модулями.

## Документация на необходимое программноеобеспечение
### движок MODX
Документайия на русском - https://docs.modx.com/current/ru/index#switchsettings

Также может быть полезна английская версия - https://docs.modx.com/current/en/index
### Bootstrap 4
https://bootstrap-4.ru/docs/4.4/getting-started/introduction/
### Gitify
Русская весрия сиьно усеченная: http://modmore.github.io/Gitify/ru/

Более полная версия, но на английском: https://docs.modmore.com/en/Open_Source/Gitify/index.html
### Git
https://git-scm.com/book/ru/v2

## Как сделать вклад
Для того чтобы работать над проектом, вам потребуеться установить http сервер, сервер MySql, PHP, git, shh, gitify и быть разегистрированым на github.

После установки и настройки програмного обеспечения, скачате код, лучше по пратаколу shh, чтобы не мучится потом с хуками.

    $ git clone git@github.com:YOU_USERNAME/pkt_site.git

Соберите проект при помощи gitify.

    $ Gitify install:modx
  
    $ Gitify package:install --all
  
    $ Gitify build --force

MODX позволяет работать как из консоли администратора, так и своим любимым редактором. Если вы используете второй метод, не забудьте, пожалуйста, собрать проект перед отправкой изменений.

    $ Gitify build --force

Хорошей идеей будет работать в отдельной ветке, чтобы всегда можно было с лёгкостью откатить изменение, или заняться чем-то другим, если логическое завершение патча, оказалось слишком трудоёмким, и хочется отдахнуть.
