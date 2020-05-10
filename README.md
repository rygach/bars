# testing_task

актуальность на 10.05.2020

== РАЗВЁРТКА

Необходим NPM
1. Закидываем в папку
2. Пишем в cmd: npm install
3. Должна появиться папка node_modules
4. возможно, потребуются перезагрузки системы/кодообозревателя
5. Пишем в cmd: npm run dev
6. Запустится локальный сервер и на нём можно будет проверить работоспособность
7. могут возникать предупреждения, которые не несут недочётов в работе

== КАКАЯ ФУНКЦИОНАЛЬНОСТЬ

Чтобы добавить:
    1. заполнить инпуты с данными по учреждениям
    2. нажать кнопку Add

Чтобы изменить: 
    1. заполнить инпуты с данными по учреждениям
    2. обязательно указать идентификатор записи
    3. нажать кнопку Update

Чтобы изменить: 
    1. обязательно указать идентификатор записи
    2. нажать кнопку Delete

Чтобы заполнить LocalStorage данными:
    1. Нажать кнопку "Load to LocalStorage"

Комментарии:
- yarn dev требует указания АБСОЛЮТНОГО пути в AJAX-запросе к файлу(hospitals.json), поэтому лучше, чтобы json-файл находился в центральной директории. Но я продублировал его ещё и в папке с pug-файлом
- scss компилируется с помощью расширения для VS Code - Sass Formatter(+ Ruby + gem). Выделяется код в style.scss ПКМ->"форматировать выделенный фрагмент"
- pug установлен через webpack