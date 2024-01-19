#WPF MVVM приложение для работы с базой данных магазина электроники 
В данном приложении предусмотрены функции удаления, добавления, редактирования и фильтрации информации о пользователях, сотрудниках, клиентах и заказах. Кроме того, в нем предусмотрена возможность авторизации сотрудников. Также есть возможность создать отчет на основе сохраненных данных.
Если база данных отсутствует, приложение автоматически создаст ее (elektonika_db_04) и заполнит тестовыми данными.
---
Технологии: WPF, MSSQL, Entity Framework
Библиотеки:
BCrypt.Net-Next – библиотека, которая предоставляет функционал для хэширования паролей с использованием алгоритма BCrypt.
EPPlus – библиотека, предназначенная для работы с файлами формата Excel (.xlsx).
Microsoft.EntityFrameworkCore.SqlServer – библиотека, которая предоставляет функционал для работы с базой данных Microsoft SQL Server через Entity Framework Core.
Microsoft.Extensions.Configuration – библиотека, предназначенная для работы с конфигурационными файлами в .NET-приложениях.
Microsoft.Extensions.DependencyInjection – библиотека, которая предоставляет функционал для реализации паттерна внедрения зависимостей (Dependency Injection)
Microsoft.Xaml.Behaviors.Wpf – библиотека, которая предоставляет набор поведений, которые позволяют легко добавлять интерактивность и функциональность к элементам пользовательского интерфейса, таким как кнопки, текстовые поля, списки и другие.

#### Для входа:
сотрудник: Johnson Emily Grace 
пароль:  zaq1xsw2

сотрудник: Brown Michael James 
пароль: 1234qw

сотрудник : Smith John Michael 
пароль: qwerty1234 

Диаграмма базы данных:
![Database](https://github.com/Vamibray/Electronics_store_db_wpf/assets/133334235/7d74404a-591f-46a9-8111-6b916380a589)

Интерфейс:
Вкладка Products 
![Products](https://github.com/Vamibray/Electronics_store_db_wpf/assets/133334235/f1a32177-e5b7-4d5a-a328-8aaac4504a4b)
Вкладка Clients 
![Clients](https://github.com/Vamibray/Electronics_store_db_wpf/assets/133334235/4757b2bf-7b58-4580-b052-dcbd422e41f6)
Вкладка Employees 
![Employees](https://github.com/Vamibray/Electronics_store_db_wpf/assets/133334235/9fcb42fb-6ad8-456e-ab0a-2451f968cdf5)
Вкладка Orders
![Orders](https://github.com/Vamibray/Electronics_store_db_wpf/assets/133334235/26bf6993-1606-45f9-8465-d44ac9960312)
Вкладка Document 
![Document](https://github.com/Vamibray/Electronics_store_db_wpf/assets/133334235/d144a265-0200-4fd5-b5fc-e6595d9f7741)
Вкладка Login
![Login](https://github.com/Vamibray/Electronics_store_db_wpf/assets/133334235/57ebecb3-5c48-44c1-8024-d87a633df744)
---
Данный проект был создан с целью обучения и приобретения практических навыков в определенной области.
