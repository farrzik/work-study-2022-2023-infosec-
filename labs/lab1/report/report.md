**Лабораторная работа №1**

**Основы информационной безопасности**

Белов Никита Дмитриевич
# Содержание
[Цель работы	1](#_Toc113715149)

[Выполнение лабораторной работы	1](#_Toc113715150)

[Выполнение задания	1](#_Toc113715151)

[Выводы	11](#_Toc113715152)


# **Цель работы**
1. Приобретение практических навыков установки операционной системы на виртуальную машину;
1. Настройки минимально необходимых для дальнейшей работы сервисов.
# **Выполнение лабораторной работы**
## **Выполнение задания**
Для установки на виртуальную машину VirtualBox операционной системы Linux (дистрибутив Rocky) в нашем случае использовалась внешняя операционная система Windows.

Сначала проверяем папку установки для машин.

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.001.png)

В VirtualBox нажимаем “Машина” - “Создать” и задаем имя “ndbelov”, соответствующее логину в дисплейном классе, для нашей будущей операционной системы. Тип - Linux, версия - Red Hat (64-bit).

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.002.png)

Задаем объем оперативной памяти 2048 МБ.![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.003.png)

Создадим новый динамический виртуальный жесткий диск, укажем тип VDI, выделим 40 ГБ.

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.004.png)

*Создание виртуального жесткого диска*

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.005.png)

*Тип виртуального жесткого диска*

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.006.png)

*Формат хранения*

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.007.png)

*Размер виртуального жесткого диска*

Первоначальные основные настройки виртуальной машины заданы, теперь запускаем нашу операционную систему, добавляем новый привод оптических дисков и выбираем образ операционной системы Rocky.

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.008.png)

Теперь запускаем созданную виртуальную машину и переходим к настройкам.

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.009.png)

Отобразился обзор установки, где мы можем задать настройки уже нашей операционной системы: задать язык раскладки, пароль для суперпользователя, выбрать часовой пояс и другие.



Язык установки.

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.010.png)

Настройки языков раскладки клавиатуры и часовой пояс.

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.011.png)



В разделе выбора программ указываем в качестве базового окружения Server with GUI, а в качестве дополнения - Development Tools.

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.012.png)

Отключаем KDUMP.

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.013.png)



Место установки ОС оставили без изменения.

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.014.png)

Включили сетевое соединение и в качестве имени узла указали ndbelov.localdomain.

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.015.png)

Указали пароль для root.

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.016.png)

Создали пользователя с логином из дисплейного класса, с правами администратора.

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.017.png)

После установки корректно перезапустили виртуальную машину и приняли условие лицензии.

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.018.png)

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.019.png)

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.020.png)



Осталось установить дополнения гостевой ОС. Для этого в виртуальной машине нажимаем “Устройства” - “Подключить образ диска Дополнений гостевой ОС”.

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.021.png)

![](Aspose.Words.1e6f01ca-3ebb-4ffa-8f05-0cc1ecae0149.022.png)
# **Выводы**
1. Приобрели практические навыки установки операционной системы на виртуальную машину;
1. Настроили минимально необходимые для дальнейшей работы сервисы.
