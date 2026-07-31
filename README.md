# brokerapp-wiki
Репозиторий используется для простой и стабильной wiki на базе git, markdown и github pages.
Страницы wiki доступны по адресу wiki.brokerapp.ru
Так же репозиторий используется для раздачи статического контента, для которого пока не нашлось своё место. Да, так лучше не делать, но в рамках имеющегося бюджета, это стабильное решение, которое экономит ресурсы на основном сервере.

## Структура репозитория
|Название папки|Описание|
|-|-|
|docs|зеркало wiki.brokerapp.ru. Все что находится в этой папке отображается в публичной части wiki|
|-widget|библиотека виджета для ОСАГО и картинки для него используемые на продуктивном стенде напрямую с wiki github'а.<br>url стенда: https://brokerapp.ru <br> url wiki: https://wiki.brokerapp.ru|
|-widget_premaster|библиотека виджета для ОСАГО и картинки для него используемые на стенде песочнице для тестирования релизов напрямую с wiki github'а<br>url стенда: https://premaster.brokerapp.ru <br> url wiki: https://wiki.brokerapp.ru|
|widget|библиотека виджета для ОСАГО и картинки для него используемые на продуктивном стенде через CDN. <br>url стенда: https://brokerapp.ru <br>url CDN: https://cdn.jsdelivr.net/gh/Neomatic-LLC/brokerapp-wiki@main/docs/widget/|
|widget_premaster|аналогичная библиотека виджета, но для песочницы pre_master (ниже подробнее)<br>библиотека виджета для ОСАГО и картинки для него используемые на стенде песочнице для тестирования релизов через CDN. <br>url стенда: https://premaster.brokerapp.ru <br>url CDN: https://cdn.jsdelivr.net/gh/Neomatic-LLC/brokerapp-wiki@main/docs/widget_premaster/|
