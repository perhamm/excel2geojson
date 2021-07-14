# excel2geojson

Преобразует файл с названием input.xlsx в файл output.geojson, пригодный для импорта в конструктор карт yandex 

Использование: 
1. Установить python3
2. Установить недостающие модули
```sh
pip3 install openpyxl
```

3. Сформатировать excel файл следующим образом:
- убрать строки вначале, должны остаться только заголовки 

  Latitude	Longitude	Description	Label	Placemark number	Color

- убедится что нет ни одного пустого поля

  Пример


  <img src="https://raw.githubusercontent.com/perhamm/excel2geojson/main/1.PNG" >


