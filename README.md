Instagram виджет
---

* Используется Slick слайдер
* Изображения загружаются с клиента через JS, что позволяет избежать блокировки IP сервера
* Вижет предназначен для работы в контексте платформы Dev2b на Yii1


Подключение
----
```
$this->widget(\dev2b\instagram\Widget::class, ['username' => '']);
```


