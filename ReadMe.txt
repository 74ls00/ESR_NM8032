
Особенности варианта.

Конденсаторы полимерные LowESR с материнской платы.

Преобразователь с 3в до 6в.
Установлена 34063 потомучто их много. При питании ниже 2.6в у ней пропадает стабилизация и снижается напряжение с повышением пульсаций, поэтому выходное около 7.5в. Далее стабилизатор 78L06 снижает до стабильных 6в.
Дроссель (L3) после 34063 обязательный для снижения пульсаций микросхемы.
Использованы элементы LR03 из за доступности. Не рекомендуется для 34063 из за их низкого напряжения. Желательно литиевый аккумулятор 3.7в. Тогда можно попробывать убрать 78L06, и перестроить преобразователь на 6в.

DA3 LM3915N работает в режиме точки, для этоко вывод 9 никуда не подключен. Для режима шкалы мощность 78L06 слишком мала.

LM3915N разрабатывалась когда ток светодиодов был больше, возможно поэтому не учтена постоянная засветка первого светодиода. Для уменьшения нулевого тока через светодиод, он закорочен через резистор R28* 2k7, сопротивление подбирается под конкретный светодиод.




Прибор NM8032 для проверки ESR электролитических конденсаторов
https://masterkit.ru/blog/articles/pribor-nm8032-dlya-proverki-esr-elektroliticheskikh-kondensatorov

https://masterkit.ru/zip/nm8032.pdf
MD5: 05FAEDD55A1C5005F3642D41380A7DFE

Об измерении ESR и доработке NM8032
https://www.sites.google.com/a/lvsystem.ru/lab/praktika/measurement/esr-meter

Обсуждение этого варианта
Собрал пробник NM8032 для проверки ESR
https://radiokot.ru/forum/viewtopic.php?f=22&t=39489&start=20