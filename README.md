## Определение сварки и обнаружение дефектов.

### Задача   

Датасет с изображениями сварки взят с сайта [kaggle](https://www.kaggle.com/datasets/sukmaadhiwijaya/welding-defect-object-detection)   
У датасета есть 2 версии, в обоих версиях по 3 класса: 0 - Bad Weld, 1 - Good Weld, 2 - Defect.   
Хотим обучить модель YOLO для определения класса сварки и обнаружения дефектов.   

### Решение   

С помощью GPU от kaggle обучил среднюю модель YOLOv8 на первой версии датасета.   
Результаты обучения и примеры предсказаний показаны ниже.
![results](https://github.com/user-attachments/assets/7a1fcbcd-e4b3-424e-a45c-efb0c441092c)
![good_weld_vid634_jpeg_jpg rf 9b7bc6b6e69b54eb707c9bab8857b7a1](https://github.com/user-attachments/assets/cabef6a6-514f-4ea4-a246-d0b57f77fdb1)
![good_weld_vid1778_jpeg_jpg rf d35cb0ff2061fb1318822c88996de9e0](https://github.com/user-attachments/assets/055c8c4a-642e-4eec-971c-e6ff0ff0dc9b)
![good-tig-welds_4_jpeg_jpg rf 3e3a5bbd002257f6e3845eaecef98355](https://github.com/user-attachments/assets/07ed4ef1-f5a0-407c-a2d9-0dbd52e75a25)
![Good-Welding-images_23_jpeg_jpg rf fdf50352e3c124ff6edab3e96257a040](https://github.com/user-attachments/assets/20673576-5f88-450e-aa59-6f5ba21fdebb)
![SampleV1_1_mp4-42_jpg rf 6e68d9186e630ffb996233ad2a593f51](https://github.com/user-attachments/assets/38cbe045-2a07-44f9-83a3-e9341ff43b33)



Чтобы улучшить качество, можно покрутить гиперпараметры, обучить на другой версии датасета, взять другую модель YOLO.   

### Описание файлов

>__results.png__ - результаты обучения.   
__welding.ipynb__ - обучение модели.     

### Библиотеки

<div id="badges">
  <img src="https://img.shields.io/badge/ultralytics-black?style=for-the-badge&logo=ultralytics"/>
  <img src="https://img.shields.io/badge/pandas-black?style=for-the-badge&logo=pandas"/>
  <img src="https://img.shields.io/badge/matplotlib-black?style=for-the-badge&logo=matplotlib"/>
  <img src="https://img.shields.io/badge/seaborn-black?style=for-the-badge&logo=seaborn"/>
</div>
