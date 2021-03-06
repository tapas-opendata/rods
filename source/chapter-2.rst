Розділ 2. Інструкції для розпорядників щодо оприлюднення набору "Перелік діючих регуляторних актів"
######################################################################################################
2.1. Підготовка, оприлюднення та оновлення набору даних
************************************************************

Набір даних "Перелік регуляторних актів" включає одну таблицю (ресурс) **list**. Таблиця містить перелік діючих регуляторних актів розпорядника із зазначенням інформації про нормативно-правові акти, якими вони були введені в дію, а також інформації про базові, повторні та періодичні відстеження. Кожним записом у таблиці є діючий регуляторний акт. Структура таблиці наведена в Таблиці 1, де name - назва колонки, title - заголовок, description - опис значень, datatype - тип даних. Типами даних є рядки тексту (string), дати (date), посилання на ресурси в мережі Інтернет (anyURI).

	.. csv-table:: Таблиця 1 - Структура таблиці (ресурсу) list
		:file: _assets/listStructure.csv
		:header-rows: 1


Відповідальні особи мають слідкувати за актуальністю інформації в таблиці й вносити зміни у разі її оновлення. Оновлення даних відбувається в наступних випадках: прийняття регуляторного акту, скасування або призупинення дії регуляторного акту, планування регуляторної діяльності, затвердження звіту про відстеження результативності регуляторного акту. Оновлення набору на порталах відкритих даних може здійснюватись планово і позапланово. 

1. У випадку планового оновлення, розпорядники самостійно визначають періодичність, відповідно до пункту 15 Положення затвердженого Постановою КМУ №835. Рекомендовано, щоб вона становила не рідше ніж 1 раз на місяць. 
2. При позаплановому оновленні - не пізніше трьох робочих днів з моменту зміни даних. Оприлюднювати набір необхідно у форматах структурованих даних - CSV, XLS(X), ODS. На портал достатньо завантажити XLS(X) файл. Його CSV версія згенеруєтья згенерується.


2.2. Шаблони та приклади заповнення таблиць
************************************************************
Завантажити шаблон таблиці можна за посиланням - :download:`list.xlsx <_assets/list.xlsx>`. Приклад заповнення доступний у `Google Таблицях <https://docs.google.com/spreadsheets/d/1KG7i_nmUWWcy7lXkzO0JlRH4BNAyIXGVXIJGXWxaoLI/edit?usp=sharing>`_. Завантажити структуру набору у форматах CSV та JSON можна за посиланнями: :download:`listStructure.csv <_assets/listStructure.csv>`, :download:`listStructure.json <_assets/listStructure.json>`.


2.3. Паспорт набору даних
************************************************************
Рекомендовано, щоб назва набору даних на Єдиному державному порталі відкритих даних починалась з "Перелік діючих регуляторних актів" та включала назву регуляторного органу розпорядника. Наприклад, "Перелік діючих регуляторних актів Житомирської міської ради". Назви ресурсів мають відповідати назві таблиці - list. Приклад заповнення паспорту набору та ресурсів наведений у Таблицях 2-3.


	.. csv-table:: Таблиця 2 - Приклад паспорту набору даних на data.gov.ua
		:header: Назва поля,Приклад заповнення

		Назва набору,Перелік діючих регуляторних актів Житомирської міської ради
		"Відомості про мову інформації, яка міститься у наборі",українська
		Частота оновлення,щомісяця
		Опис,"Набір містить перелік діючих регуляторних актів Житомирської міської ради із зазначенням інформації про нормативно-правові акти, якими вони були введені в дію, а також інформації про базові, повторні та періодичні відстеження."
		Підстава та призначення збору інформації,"Інформація набору є результатом і характеризує діяльність регуляторних органів відповідно до Закону України ""Про засади державної регуляторної політики у сфері господарської діяльності""."
		Ключові слова,"акт, звіт, відстеження, регуляторний акт, регуляторна політика"
		Відповідальна особа,Симоненко Олена Петрівна
		Адреса електронної пошти відповідальної особи,o.symonenko@example.gov.ua


	.. csv-table:: Таблиця 3 - Приклад паспорту ресурсу list
		:header: Назва поля,Приклад заповнення

		Назва ресурсу,list
		Опис,"Таблиця містить ідентифікатори, назви, дати набрання чинності регуляторними актами, посилання на публікації мережі Інтернет і друкованих виданнях, назви та ідентифікатори регуляторних органів, дати затвердження звітів базового, повторного та періодичних відсежень, посилання на звти та інше."
		Формат,XLSX

