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


  <img src="https://user-images.githubusercontent.com/499192/57450172-1a955f80-725e-11e9-9fed-267179bdab15.gif" alt="Example of uploading image to GitHub's CDN" width="500px">


