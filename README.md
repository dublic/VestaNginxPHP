# VestaNginxPHP
Файлы по связке VestaCP+Nginx+PHP

По размещению сайта(-ов)
Если трафик вашего сайта "размазан" по России, то логичней сайт размещать в центре России, а именно https://vk.cc/9CfnUM
Если трафик направлен на Мск, Спб и Европу, то хостинг берем тут -> 
Домены для проектов (как вы догадались) регистрируем тут -> https://vk.cc/7oyx2t

Папки с файлами


Конфиги для Nginx-PHPfpm
На кажду CMS (или сайт) три конфига. 
Почему? За время жизни, интернет-проект пребывает в трех состояниях: настройка, разработка и продакшен
Соответственно и мы содали три конфига для хоста и/или приложения в целом.

name_app.tpl(.stpl)     - для режима инсталяции и первичных настроек, проверка работы по HTTP и по HTTPS
name_app_dev.tpl(.stpl) - для режима разработки, обрезаются IP или целые подсети, пишется в логи всё 
name_app_ssl.tpl(.stpl) - для режиа продакшен, в логи только нужное, принудительный SSL (httpS) для всех запросов

Благодарность
Весь мир держится на доброте и взаимопомощи. Будьте благодарны если работа других людей помогла вам. Миром правят позитивные люди, негативные всего-лиш временные наблюдатели. Послушай Аркадий Коц Стены и песенку Улыбка из м/ф Крошка енот

Как нас отблагодарить? 
Есть несколько вариантов, выбери наиболее удобный:
- пройтись по ссылкам и заказать услуги
- протестировать и указать на ошибки (если хорошо знаком с php и директивами nginx)
- предложить дополнения/правки/улучшения (если хорошо знаком с php и директивами nginx)
- перейти по ссылке и внести денюжек сколько не жалко https://yasobe.ru/na/vestaserver
- обратиться к нам за услугами https://vk.com/dublicru 
