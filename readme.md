# Группа №3
## Информационная система "Алиса"
### Структура базы данных
![Структура БД](ER_diagram.png)

### База данных состоит из четырёх таблиц

![](general_form.png)

* ###Students 
  * id (_Идентификационный номер записи_)
  * first_name (_Имя учащегося_)
  * last_name()
  * id_class()
* ###Classes 
  * id (_Идентификационный номер записи_)
  * level (_Класс_)
  * symbol (_Буква_)
* ###Subjects
  * id (_Идентификационный номер записи_)
  * Subject (_Название урока_)
* ###Schedule
  * id (_Идентификационный номер записи_)
  * id_week (_День недели_)
  * time_start (_Время начала урока_)
  * id_class (_Класс_)
  * id_subject (_Название урока_)
____
##Работа с информационной системой
В каждой таблице реализована возможность :
* Добавление
  * ![](add_button.png) 

* Удаление
  * ![](delete_button.png)

* Редактирование
  * ![](submit_button.png)

* Каждой таблицей поддерживается полноэкранный режим
![](full_screen_mode.png)

* При этом остаётся возможность переключения между таблицами
![](switching.jpg)

* Все пересекающиеся поля таблиц являются ссылочными и сделаны выпадающими списками
![](table_intersection.png)

#Над проэктом работали:

* # Александр Башлаев GUI, Рабочий код
* # Рафаэль  **_Рабочий код_**
* # Артём Михайлов  _**Рабочий код**_
* # _**Алексей Осипцов Рабочий код, readme.md**_
