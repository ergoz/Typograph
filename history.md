v.2.2.1
[+] Правило «Оторвать тире от слова» теперь работает корректно.
[+] Расстановка дефисов в предлогах «из-за», «из-под», «по-над», «по-под».
[+] Привязка «-либо», «-нибудь» к вопросам кто, что, где, когда, почему, зачем, кем, чем.
[+] В сокращения добавлены «зам», «см» (заместитель, смотреть).
[+] В сокращения перед числами добавлено «гл» (глава).
[*] Фикс: Удаление повторяющихся знаков препинания в конце предложения.
[*] Фикс: Удаление повторяющихся знаков написанных через любое количество пробелов. Троеточие и другие исключения учтены.
[+] Немного оптимизирован код.

v.2.2.0
[*] Исправлена ошибка в выставлении опций и соответствующая документация.
[+] Интеграция с CakePHP.
[*] Типограф больше не будет удалять переводы строк, если строка начиналась или оканчивалась скобкой.
[*] Приведены в порядок различные плагины и инструкции по интеграции.
[*] Фикс: Ошибочно принимаемые за сокращения начала слов.
[*] Фикс: Степени + единицы измерения.
[*] Фикс: Неразрывные формы собственности и названия огранизаций. 
[-] Убрано правило «Оторвать тире от слова». Контрпример: «газо- и электросварка»
[+] Прямая речь.
[+] removeAllSafeBlocks() для очистки стандартного набора безопасных блоков.
[+] Не разрывать IP-адреса.

v.2.1.0
[+] Вложенные кавычки.
[-] Склейка ёлочек (временно убрано).
[+] Притягивание чисел к знаку умножения.
[+] Запятые до «а» и «но».
[+] Притягивание «;» к предшествующему слову.
[*] Троеточием теперь считается от трёх до пяти точек.
[+] Убирает лишние знаки: «??» в «?», «!!!!» в «!!!».
[+] К списку сокращений добавлена иллюстрация («илл.»).
[+] Улучшено типографирование чисел прописью и денежных сумм.
[+] Тире нельзя отрывать от стоящего перед ним слова.
[-] Убрано форматирование телефонных номеров.
[*] Исправлена обработка «МГУ, ГУМ».
[+] Опциональное преобразование спецсимволов в коды HTML.
[+] Обработка «уе» в денежных суммах.
[+] !? => ?!
[+] К единицам измерения добавлены dpi, px.
[+] Правильные апострофы в «LO'Лайт».

v.2.0.7
[+] Оторвать скобку от слова. (Zav)
[+] Дополнен список сокращений. (Спасибо Zav)
[+] Нельзя переносить единицу измерения: 10 кг, писать раздельно. (Спасибо Zav)
[+] Добавление пропущенных точек у сокращений. (Спасибо Zav)
[+] Обработка квадратных и кубических(и др. степеней) метров(и др единиц измерения): 10м2.
[+] Плагин для WordPress. (Спасибо MAX)
[+] Модуль для Drupal. (Спасибо MAX)
[+] Коррекция тел./факс: (812). (Спасибо Zav)
[+] Опция для замены всех ё на е. $typo->convertE(true); (Спасибо Zav) См. также: http://diamondsteel.ru/useful/handbook/5.html#5.5.3.
[*] fix: обработка закрывающей кавычки перед ;
[*] Код для PHP4 больше обновляться не будет... если конечно кто-нибудь меня не попросит.
[*] Класс переименован в Typographus из-за многочисленных конфликтов имён при использовании в популярных фреймворках.

v.2.0.6, v.1.0.6
--------------------------------------------------------------------------------
[*] fix: Замена на &nbsp; вместо того, что передано в конфиге
[+] Версия ПО пишется неразрывно с буковкой v. и названием ПО
[*] fix: Неправильная обработка кавычек в выражении: да "тест"- уже
[*] fix: ("слово") -> ("слово»)
[+] Не отделяем табл. и рис. от номера
[+] К словам теперь приятягиваются ?!:,

v.2.0.5, v.1.0.5
--------------------------------------------------------------------------------
[*] fix: "тест"<tag>"тест" (Спасибо Reki за багрепорт)

v.2.0.4, v.1.0.4
--------------------------------------------------------------------------------
[+] Замена +- на соотв. знак
[+] «Слово  !» => «Слово!» 
[+] К аббревиатурам добавлены: НПФ, НИИ

v.1.0.3
--------------------------------------------------------------------------------
[+] Версия для PHP4 приведена к версии для PHP5 насколько это возможно.

v.2.0.3
--------------------------------------------------------------------------------
[+] В список форм собственности добавлен ИП.
[*] fix: притягивание запятых к кавычкам, апострофам, знакам ™ и ®. (Спасибо grasshopper за багрепорт)

v.2.0.2
--------------------------------------------------------------------------------
[*] fix: Пофиксены возможные проблемы с кодировкой. (Спасибо, eagle)

v.2.0.1
--------------------------------------------------------------------------------
[*]Теперь конвертируются абсолютно любые кавчки и ёлочки в правильно расставленные ёлочки.
[*]Число точек при замене на троеточие расширено до 5-и. (По заявкам трудящихся)

v.2.0.0
--------------------------------------------------------------------------------
[*] Переход на PHP5.
[+] Оформлен в виде класса.
[*] Подправлены плагины Smarty для работы с классом.
[+] Обработка текстов не в кодировке WINDOWS-1251.
[+] Склейка ёлочек: "test "quote"" -> «test «quote»
[+] Неразрывный пробел после инициалов, слепка инициалов.
[+] Неразрывные названия организаций и абревиатуры форм собственности.
[+] Нельзя отрывать имя собственное от относящегося к нему сокращения. Например: тов. Сталин, г. Воронеж. Ставит пробел, если его нет.
[+] Не разделять 2007 г., ставить пробел, если его нет.
[+] Слепка скобок со словами.
[+] Замена 1/2 1/4 3/4 на спецсимволы.
[+] Русские денежные суммы, расставляя пробелы в нужных местах.
[+] Не отделять стр. и с. от номера странцы.
[*] Приподнятые ™ и ®.
[*] Замена (c) с русской "c".

v. 1.0.3
--------------------------------------------------------------------------------
[*] fix: v.1.0.2

v. 1.0.2
--------------------------------------------------------------------------------
[*] fix: "новый тариф*"
[*] fix: "personal:"
[*] fix: "c:\www\sites\"
[*] fix: "ICQ #"
[*] &minus; заменён &ndash;, соответствующие символы тоже.
[+] Разнос неправильно расставленных кавычек. (вася"пупкин") => (вася "пупкин")
[+] Дополнен список предлогов и союзов, после которых надо ставить неразрывный пробел.
[+] Дополнен список частиц
[+] Расстановка запятых. (Слово ,слово) (Слово,слово) (Слово , слово) => (Слово, слово)
[+] тел: 81231231212 -> <span style="white-space:nowrap">тел: 8 (123) 123-12-12</span>

v. 1.0.1
--------------------------------------------------------------------------------
[+]Много пробелов -> один пробел.
[*]Пофиксена проблема с некорректной работой на *nix хостинге. Спасибо -=Ustas=- ( http://vingrad.ru/@-=Ustas=- )

v. 1.0
--------------------------------------------------------------------------------
Первый релиз