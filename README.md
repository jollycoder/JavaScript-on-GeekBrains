# Домашнее задание 
1.	С помощью jQuery cоздать контрол, работающий с вкладками. Пример - [http://dimox.name/examples/universal-jquery-tabs-script](http://dimox.name/examples/universal-jquery-tabs-script). Можно использовать любую анимацию, методы show, hide и подобные. Код примера желательно не смотреть.
2.	Необходимо скачать, прилагаемый файл  validator.php. Самостоятельно разобраться в формате данных который он отдает. С помощью ajax запросов к этому файлу необходимо реализовать валидатор формы.
```php
array(
'username' => 'Somebody',
'password' => 'mypassword',
'email' => 'some@some.ru',
'gender' => 'm',
'credit_card' => '9872389-2424-234224-234', 
'bio' => 'This is good! I think I will switch to another language'
)
```
Ограничения:
1. Все поля обязательные
2. Пол - 1 символ (M, Ж)
3. Email и credit card должны быть указаны в соответствующем формате.
4. Логин и пароль, мин длинна 6 символов, макс - 100
