# Final project for ITMO University

#Введение
Данное веб-приложение предназначено для автоматизации работы онлайн школы, предоставляющей пользователям сервис подписки на курсы различной тематики. 
Для разработки приложения была использована технология создания веб-приложений и веб-сервисов ASP.NET 4.6 и ASP.NET MVC 5 фреймворк  от компании Microsoft.  
Локальная база данных была создана при помощи методологии CodeFirst и включила в себя 7 сущностей, приемущественно находящихся по отношению друг к другу в связи «один ко многим». 
Разработка веб-интерфейса приложения осуществлялась посредством HTML5, CSS, JavaScript, JQuery,  а также инструментов Bootstrap и HTML5Up и механизма визуализации ASP.NET Razor. 
Полный цикл создания приложения происходил в интегрированной среде разработки Microsoft Visual Studio 2015 Community Edition.


#Задачи

•	Разработать базу данных для хранения информации о подписчиках, курсах, учителях.
•	Обеспечить интерфейс и навигацию по страницам веб-приложения для стороннего пользователя и администрации сайта.
•	Разработать возможности добавления, редактирования данных в базе администрацией приложения.
•	Разработать возможность поиска данных в каталоге для стороннего пользователя.
•	Обеспечить грамотный доступ администрации к данным приложения.
•	Обеспечить простой и понятный интерфейс работы с приложением.


#Функции приложения

В данном приложении реализована функция учета подписок. Каждый подписчик самостоятельно выбирает курс в каталоге по названию, категории или учителю и через пользовательский интерфейс записывается в базу данных с указанием адреса электронной почты, своего имени и названия курса, тем самым оставляя запрос на подписку. Администратор приложения, увидев нового пользователя в базе данных, оформляет ему подписку и на указанный email высылает ссылку доступа к материалам курса.　


#Работа с приложением. Пользовательский интерфейс

Главная страница:

➢	Чтобы перейти в Главное Меню, сайта нажмите   кнопку меню   в  правом верхнем углу.
➢	В открывшемся окне нажмите About, чтобы перейти по якорю в раздел О приложении.
➢	Чтобы перейти в Каталог, нажмите Browse Catalog.
➢	Чтобы перейти в раздел Контакты, нажмите Contacts.
➢	Чтобы вернуться в раздел Главная, нажмите HOME или LEARNIT.
➢	В раздел Главная можно вернуться из другого раздела главной страницы или других страниц приложения нажав на логотип сайта LEARNIT, расположенный в левом верхнем углу каждой страницы. 
➢	Стрелка           , расположенная снизу у нижнего края разделов главной страницы, предназначена для перехода по якорю к следующему разделу главной страницы. 
➢	Вы можете перейти в Каталог курсов с главной страницы, нажав на ссылку Browse Catalog, расположенную в центре раздела Главная на главной странице приложения.
➢	На страницы Каталога можно также перейти из раздела About, кликнув по ссылкам, указывающим на статистику сайта: 
➢		- Нажав на цифру, указывающую на статистику по количеству курсов, вы перейдете на страницу поиска курсов по имени.
➢		- Нажав на цифру, указывающую на статистику по количеству областей знаний, вы перейдете в каталог курсов по тематикам.
➢		- Нажав на цифру, указывающую на статистику по количеству представленных на сайте учеников, вы перейдете на страницу поиска курсов по учителям. 
      
➢	Чтобы написать в службу поддержки сайта, перейдите в раздел Контакты через главное меню сайта     и нажмите Contacts. В данный раздел вы также можете перейти с любой страницы приложения, спустившись в самый низ страницы, на которой находитесь. 
➢	В разделе Контакты, кликнув на ссылку с адресом электронной почты, вы перейдете к вашему почтовому клиенту.


Страница каталога:

➢	На странице каталога, чтобы выбрать курс, воспользуйтесь выпадающим окном: выберите категорию и нажмите  Filter.
➢	Со страницы каталога вы можете перейти по ссылке на страницу поиска курса по имени – для этого нажмите Courses by name. 
➢	Также со страницы каталога вы можете перейти по ссылке на страницу поиска курса по учителям – для этого нажмите Teachers. 
➢	На страницах каталога по имени, категории или учителям после фильтрации нажмите на картинку курса, чтобы перейти на страницу выбранного курса. Вы также можете перейти по ссылке на страницу учителя этого курса, кликнув на ссылку с его именем. 

Страница курса:

➢	На странице курса вы можете посмотреть информацию о данном курсе, дату создания курса, категорию, к которой относится курс. Вы также можете перейти по ссылке на страницу учителя данного курса.
➢	Чтобы подписаться на курс, нажмите Subscribe.


Страница подписки на курс:

➢	Чтобы оформить заявку на курс, заполните форму и нажмите Send. В случае успешной отправки сообщения произойдет переход на страницу каталога курсов. На адрес указанной вами электронной почты будет отправлена ссылка с доступом к материалам курса.


Страница учителя:

➢	Вы можете перейти на страницу учителя по ссылке через каталог или страницу курса. На странице учителя вы найдете информацию о нем и его образовании.



#Работа с приложением. Администрирование сайта.

Страница входа для администраторов:

➢	Для администрирования сайта необходимо ввести адрес https://домен/Account/login в URL строку вашего браузера.
➢	Введите выданный вам администратором email и пароль. Нажмите Log In.


CRUD для курсов:

➢	Выполнять операции создания, редактирования и удаления курсов можно на страницах Courses by Category, Courses by Name, Courses by Teacher, перейдя на них по соответствующим ссылкам в верхнем меню страницы администратора.
➢	На этих страницах вы можете также посмотреть статистику сайта: количество курсов, учителей, категорий,  подписчиков, подписок. 

Создание курсов:
	
➢	Чтобы создать новый курс, перейдите по ссылке Photo на верхней панели меню.
➢	Нажмите Upload Photo, чтобы загрузить новую фотографию для курса. В разделе Upload Photo, нажмите Обзор, чтобы выбрать фотографию на вашем компьютере. Нажмите Submit для отправки фотографии на сервер. 
➢	Если необходимо создать страничку учителя для нового курса, загрузите также фотографию учителя. Затем перейдите по ссылке Teachers на верхней панели меню. Нажмите Create New, для перехода в раздел создания странички учителя. Введите Имя в поле Name, название ВУЗа в поле Graduated информацию об учителе в поле About и выберите фотографию в выпадающем списке Photo. Нажмите Create, чтобы сохранить.
➢	Если необходимо создать новую категорию для курса, перейдите по ссылке Categories в верхнем меню. Нажмите Create New, введите в предложенное поле название категории, выберите из выпадающего списка область и нажмите Create, чтобы сохранить.
➢	Если необходимо создать новую область для курса, перейдите по ссылке Scientific Fields в верхнем меню. Нажмите Create New, введите в предложенное поле название области и нажмите Create, чтобы сохранить.
➢	Вернитесь на страницу Courses by Category, Courses by Name или Courses by Teacher, чтобы продолжить создание нового курса. Нажмите Create New, чтобы перейти в соответствующий раздел. Заполните предложенные поля и нажмите Create, чтобы сохранить информацию в базе данных. Если необходимо вернуться к списку курсов, нажмите Back To List.


Регистрация подписок

➢	Чтобы зарегистрировать подписку на курс, перейдите по ссылке Subscribers, выберите адрес электронной почты нового пользователя, скопируйте его и перейдите по ссылке Subscriptions в верхнем меню страницы. 
➢	Нажмите Create New, чтобы зарегистрировать подписку на курс. 
➢	В разделе Create заполните предложенную форму и нажмите На странице каталога, чтобы выбрать курс, воспользуйтесь выпадающим окном: выберите категорию и нажмите  Create, чтобы сохранить.


#Заключение

По причине сжатых сроков не удалось:
	
➢	Обеспечить должную безопасность для администрирования сайта.
➢	Реализовать полную автоматизацию подписки на курсы пользователями с автоматической отправкой им ссылки доступа к материалам курса по электронной почте.
➢	 Реализовать регистрацию пользователей в сети, в том числе посредством сторонних сервисов (Facebook, Google).

После доработки данное веб-приложение может использоваться организацией, предоставляющей сервис онлайн образования.
