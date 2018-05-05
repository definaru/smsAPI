API SMS оповещений
=====================
![screenshot of sample](http://www.starline.center/admin/users/19042015-2.png)
---
## The sms processor on the Yii2 framework
---
Название файла  | Содержание файла
----------------|----------------------
Messager.php    | Класс ответственный за обработку данных
Callback.php    | Данный скрипт позволяет принимать callback оповещения
Error.php       | Рашифровщик кода ошибок

---
```php
<?=Messager::delCallback(); // Удалить обработчик, внесенный вами ранее ?>
<?=Error::message(); // выведет понятный текст ошибки вместо цыфры ?>
```
