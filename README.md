## Определение сварки и обнаружение дефектов.

### Задача   

Датасет с изображениями сварки взят с сайта [kaggle](https://www.kaggle.com/datasets/sukmaadhiwijaya/welding-defect-object-detection)   
У датасета есть 2 версии, в обоих версиях 3 класса: 0 - Bad Weld, 1 - Good Weld, 2 - Defect.   
Хотим обучить модель YOLO для определения класса сварки и обнаружения дефектов.   

### Решение   

С помощью GPU от kaggle обучил среднюю модель YOLOv8 на первой версии датасета.   
Результаты обучения показаны ниже.
![results](https://github.com/user-attachments/assets/7a1fcbcd-e4b3-424e-a45c-efb0c441092c)
