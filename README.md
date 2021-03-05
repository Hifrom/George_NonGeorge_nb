# George_NonGeorge_nb
Задача классификации изображений с Георгием/НеГеоргием   
Используется Jupyter Notebook    

## Разбор
Для обучения сети запустить Train_George.ipynb  
Для создания csv файла - create_csv.ipynb  
Для инференса - test.ipynb  
Для парсинга данных - Parser.ipynb  

## Запуск обучения  
Первоначально необходимо загрузить тренировочную и тестовую выборки (приватная ссылка находится в Data/Data.txt) и добавить два фолдера (train и test) в папку Data  
Запустить Train_George.ipynb, предварительно изменив гиперпараметры, если это необходимо   
Каждые epoch_accuracy будет сохраняться обученная модель и записываться результаты точности на тренировочной и тестовой выборки в log.txt. Также сохраняется состояние модели для лучшего значения точности на тестовой выборке
Ждать c:

## График обучения сети
После 140 эпох обучения точность составила 95% на предобученной архитектуре  Resnet50:   
![alt text](https://github.com/Hifrom/George_NonGeorge/blob/main/Acc.jpeg "График обучения сети")
