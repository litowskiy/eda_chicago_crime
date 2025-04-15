Анализ преступности в Чикаго  
Количество строк: 239,558  
Количество столбцов: 22
Описание данных:  
**ID** – отображает уникальный идентификатор преступления. Тип переменной – категориальная, номинативная.  
**Case Number** – отображает номер полицейского дела, связанного с преступлением. Тип переменной – категориальная, номинативная.  
**Date** - отображает дату и время совершения преступления. Тип переменной – категориальная, номинативная (временная).  
**Block** – отображает улицу и номер дома, где произошло преступление. Тип переменной – категориальная, номинативная.  
**IUCR** – отображает единый код отчетности о преступлениях штата Иллинойс. Тип переменной – категориальная, номинативная.  
**Primary Type** – отображает категорию преступления. Тип переменной – категориальная, номинативная.  
**Description** – отображает уточнение к категории преступления (описание преступления). Тип переменной – категориальная, номинативная.  
**Location Description** – отображает место совершения преступления, его описание. Тип переменной – категориальная, номинативная.  
**Arrest** – отражает, был ли преступник задержан, выражена True(задержан) или False(не задержан). Тип переменной – категориальная, бинарная.  
**Domestic** – отражает связь преступления с домашним насилием, выражена True(связано с д/н) или False(не связано с д/н). Тип переменной – категориальная, бинарная.  
**Beat** – отображает конкретный участок полицейского патрулирования. Тип переменной – количественная, дискретная.  
**District** – отображает более крупный полицейский округ, в котором произошло преступление. Тип переменной – количественная, дискретная.  
**Ward** – отображает политический район, где было зарегистрировано преступление. Тип переменной – количественная, дискретная.  
**Community Area** – отображает область сообщества, где было совершено преступление. Тип переменной – количественная, дискретная.  
**FBI Code** – отображает классификационный код ФБР для типа правонарушения. Тип переменной – категориальная, номинативная.  
**X Coordinate, Y Coordinate** – отображают геопространственные координаты по осям X и Y в городской системе. Тип переменной – количественная, непрерывная.  
**Year** – отображает год совершения преступления. Тип переменной количественная, дискретная.  
**Updated On** – отображает дату последнего обновления записи о преступлении. Тип переменной – категориальная, номинативная (временная).  
**Latitude, Longitude** – отображают GPS координаты для локализации места преступления по широте и долготе. Тип переменной – количественная, непрерывная.   
**Location** – отображает координаты в виде кортежа (широта, долгота). Тип переменной – категориальная, номинативная.

О файлах:  
EDA_Chicago_Crime.ipynb - файл с анализом  
chicago_heatmap.html - тепловая карта  
chicago_map.html - карта с пинами мест преступлений  
chicago_map_types.html - карта с пинами мест преступлений + тип преступления  
https://www.kaggle.com/datasets/georgehanyfouad/crime-prediction-in-chicago-in-2022 - Датасет  
