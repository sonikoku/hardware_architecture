### Задача 1. Навигация по основным разделам

![alt text](screenshots/image1.png)

* Версия UEFI BIOS: `N46ET09W` (дата: `2024-01-22`)
* Серийный номер (System-unit serial number): `PF12345`
* Тип CPU: `Intel(R) Core(TM) CPU` (`1.X00GHz`)
* Установленная память: `8192MB`
* Статус UEFI Secure Boot: `On`

> точный путь: `Main`

### Задача 2. Смена порядка загрузки

![alt text](screenshots/image2.png)

USB HDD перенесен на первое место, NVMe0 на второе

> точный путь: `Startup -> Boot -> Boot Priority Order`

### Задача 3. Включение/выключение Secure Boot

![alt text](screenshots/image3.png)

Требуется перезагрузка

> точный путь: `Security -> Secure Boot -> Secure Boot`

### Задача 4. Установка пароля супервизора

![alt text](screenshots/image4.png)

> точный путь: `Security -> Password -> Supervisor Password`

### Задача 5. Сброс на заводские настройки

![alt text](screenshots/image5.png)

> точный путь: `Restart -> Load Factory Defaults`

сбросился порядок загрузки к исходному

![alt text](screenshots/image6.png)

### Задача 6. Управление встроенными устройствами

![alt text](screenshots/image7.png)

> точный путь: `Config -> USB -> Always On USB`

### Задача 7. Режим работы SATA/NVMe

![alt text](screenshots/image8.png)

В эмуляторе ThinkPad T14s Gen 5 нет настройки режима работы накопителей

### Задача 8. Временное меню загрузки (эмуляция F12)

![alt text](screenshots/image9.png)

> точный путь: `Startup -> Boot Device List F12 Option`

### Задача 9. Просмотр системных логов

![alt text](screenshots/image10.png)

(Simulator not support)

> точный путь: `Main -> BIOS Event log`

### Задача 10. Полный сценарий: подготовка к переустановке ОС

1. Сбросить настройки на Factory Defaults

![alt text](screenshots/image11.png)

2. Включить Secure Boot

![alt text](screenshots/image12.png)

3. Установить Supervisor Password 

![alt text](screenshots/image13.png)
![alt text](screenshots/image13_1.png)

4. Поставить USB первым в порядке загрузки

![alt text](screenshots/image14.png)

5. Сохранить и выйти

![alt text](screenshots/image15.png)

6. Снова войти, проверить настройки, сбросить пароль и вернуть порядок загрузки

![alt text](screenshots/image16.png)

>изменения сохранились

возврат настроек:

![alt text](screenshots/image17.png)
![alt text](screenshots/image18.png)
