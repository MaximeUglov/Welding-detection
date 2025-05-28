## Определение сварки и обнаружение дефектов.

### Задача   

Датасет с изображениями сварки взят с сайта [kaggle](https://www.kaggle.com/datasets/sukmaadhiwijaya/welding-defect-object-detection)   
У датасета есть 2 версии, в обоих версиях по 3 класса: 0 - Bad Weld, 1 - Good Weld, 2 - Defect.   
Хотим обучить модель YOLO для определения класса сварки и обнаружения дефектов.   

### Решение   

С помощью GPU от kaggle обучил среднюю модель YOLOv8 на первой версии датасета.   
Результаты обучения показаны ниже.
![results](https://github.com/user-attachments/assets/7a1fcbcd-e4b3-424e-a45c-efb0c441092c)

Чтобы улучшить качество, можно покрутить гиперпараметры, обучить на другой версии датасета, взять другую модель YOLO.   

### Описание файлов

>__best.pt__ - веса лучшей модели.   
__results.png__ - результаты обучения.   
__welding.ipynb__ - обучение модели.     

### Библиотеки

<div id="badges">
  <img src="https://img.shields.io/badge/ultralytics-black?style=for-the-badge&logo=ultralytics"/>
  <img src="https://img.shields.io/badge/pandas-black?style=for-the-badge&logo=pandas"/>
  <img src="https://img.shields.io/badge/matplotlib-black?style=for-the-badge&logo=matplotlib"/>
  <img src="https://img.shields.io/badge/seaborn-black?style=for-the-badge&logo=seaborn"/>
</div>
