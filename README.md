# excel2geojson

Преобразует файл с названием input.xlsx в файл output.geojson, пригодный для импорта в конструктор карт yandex 

Использование: 

0. Скачать архив с программой и поместить все файлы в одну папку
1. Установить python3
2. Установить недостающие модули
```sh
pip3 install openpyxl
```

3. Сформатировать excel файл следующим образом:
- убрать строки вначале, должны остаться только заголовки 

  Latitude	Longitude	Description	Label	Placemark number	Color

- убедится что нет ни одного пустого поля (метки - label - не должны быть пустыми)

  Пример


  <img src="https://raw.githubusercontent.com/perhamm/excel2geojson/main/1.PNG" >

- поместить полученный файл, назвав его input.xlsx, в папку с программой
- запустить так (из папки с программой)
 ```sh
python3 py2kml.py
```
- должно быть написать в выводе - что результат выполнения - успешен

  Пример

  <img src="https://raw.githubusercontent.com/perhamm/excel2geojson/main/2.PNG" >

- загрузить полученный output.geojson в конструктор карт яндекса

  Пример результата

  <img src="https://raw.githubusercontent.com/perhamm/excel2geojson/main/3.PNG" >
