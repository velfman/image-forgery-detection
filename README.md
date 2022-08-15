# Распознавание изображений, отредактированных в графических редакторах
Данный проект по артефактам сжатия изображений с помощью ELA (Error Level Analysis) позволяет определить факты редактирования с визуализацией результатов проверки и вероятностной оценкой принадлежности к одному из двух классов - оригинальному или обработанному.
Локальное использование возможно с помощью Predict.ipynb с заменой image_name на название изображения, которое необходимо проверить.
Ссылка на файл модели: https://disk.yandex.ru/d/4NAZXIeoAJt-yQ
![Метрики VGG-16, 30ep, le1e-4, 2600 CASIA-2](https://user-images.githubusercontent.com/109477509/184604321-55adb72e-13a1-4f33-835d-3891c1943b5e.JPG)
![Accuracy-Loss](https://user-images.githubusercontent.com/109477509/184604218-3b1abb0c-f515-45b6-9947-3f51330ae40d.png)
![Confusion matrix](https://user-images.githubusercontent.com/109477509/184604259-614178d9-be30-4a1c-9a61-b804e62e4cdb.png)
![ROC-AUC](https://user-images.githubusercontent.com/109477509/184604296-67410b18-02de-4b1c-b781-ce495eaf246f.png)
