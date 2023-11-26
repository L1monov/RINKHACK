<h4>Реализованная функциональность</h4>
<ul>
    <li>Автоматизированное создание и настройка задач</li>
    <li>Чат на вебсокетах</li>
    <li>Проект готов к масштабированию</li>
</ul> 
<h4>Особенность проекта в следующем:</h4>
<ul>
 <li>Автоматизация в управлении проектами.</li>
 <li>Коммуникации ( чаты на вебсокетах ( в каждом проекте, в каждой площадке, также и личные чаты ))</li>
 <li>Поточное управление процессом</li>  
 <li>Автораспределение KPI ( настраиваете и потом просто выдаете тэги )</li>  
 <li>Выгрузка отчетов о проделанной работе за любые периоды</li>  
 <li>Интеграция с системой контроля версий ( к примеру Git )
</li>  
 </ul>
<h4>Основной стек технологий:</h4>
<ul>
    <li>LAMP</li>
	<li>HTML, CSS, JavaScript, JQuery.</li>
	<li>PHP 8.2, MySQL.</li>
	<li>Laravel</li>
	<li>Tailwind CSS, PostCSS, bootstrap</li>
	<li>Babel, Vite.</li>
	<li>БЭМ.</li>
	<li>Pusher JS ( websocket )</li>
	<li>Vue (Nuxt.js)</li>
	<li>Git.</li>
	<li>Gitlab.</li>
  
 </ul>
<h4>Демо</h4>
<p>Демо сервиса доступно по адресу: ws-icm.ru/demo/ </p>
<p>Реквизиты тестового пользователя: email: <b>test@mail.ru</b>, пароль: <b>123123123</b></p>




СРЕДА ЗАПУСКА
------------
1) развертывание сервиса производится на debian-like linux (debian 9+);
2) требуется установленный web-сервер с поддержкой PHP(версия 7.4+) интерпретации (apache, nginx);
3) требуется установленная СУБД MariaDB (версия 10+);
4) требуется установленный пакет name1 для работы с...;



------------
1. Развертывание сервиса
Установите Laravel и необходимые зависимости:

bash
Copy code
composer create-project --prefer-dist laravel/laravel your-project-name
cd your-project-name
Установите Node.js и npm (если еще не установлены):

------------
Установите Node.js и npm, затем выполните:

bash
Copy code
npm install
2. Web-сервер
Laravel поставляется с встроенным сервером, который вы можете использовать для разработки. Если вам нужен Apache или Nginx, настройте их соответствующим образом для Laravel. Официальная документация Laravel содержит подробные инструкции.

------------
3. СУБД MariaDB
Установите MariaDB:

bash
Copy code
sudo apt-get install mariadb-server mariadb-client
Запустите MariaDB и выполните безопасную настройку:

bash
Copy code
sudo systemctl start mariadb
sudo mysql_secure_installation
Создайте базу данных:

sql
Copy code
mysql -u root -p
CREATE DATABASE mynewdb;
------------
4. Выполнение миграций
Создайте миграции в Laravel:

bash
Copy code
php artisan make:migration create_your_table_name
Заполните миграции данными и выполните их:

Используйте миграции Laravel для заполнения базы данных.

------------
5. Установка зависимостей проекта
Установите Composer (если не установлен):

Следуйте инструкциям на getcomposer.org.

Установите зависимости Laravel:

bash
Copy code
composer install
Установите зависимости Vue.js:

bash
Copy code
npm install
Скомпилируйте ресурсы Vue.js:

bash
Copy code
npm run dev
Теперь у вас должен быть проект Laravel с Vue.js, установленный и настроен в соответствии с вашими предыдущими инструкциями. Не забудьте настроить ваш веб-сервер для Laravel и выполнить миграции для базы данных.

------------
composer install
~~~

РАЗРАБОТЧИКИ

<h4>Тимошев Рифат fullstack/backend https://t.me/userix61 </h4>

<h4>Тимошев Далил front(vue) https://t.me/timoshevdalil </h4>

<h4>Стокозов Валентин backend https://t.me/WebStudioICM_valentin </h4>

<h4>Субботин Владислав front(vue) https://t.me/Gipsokartonxx </h4>

<h4>Бабаханян Айк design https://t.me/horovac </h4>


