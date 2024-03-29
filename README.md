# Распознавание изображений, отредактированных в графических редакторах

# Recognition of images edited in graphic editors
Данный проект по артефактам сжатия изображений с помощью ELA (Error Level Analysis) позволяет определить факты редактирования с визуализацией результатов проверки и вероятностной оценкой принадлежности к одному из двух классов - оригинальному или обработанному.
Данный проект имеет ряд версий, с которыми вы можете ознакомиться выше. Модель с наиболее высокими показателями качества - "VGG-16, 30ep, le1e-4, 2600 CASIA-2". Параметры данной модели соответствуют её названию - она основана на архитектуре VGG-16, обучение проходило в 30 epoch, датасет состоял из 2600 изображений модифицированного датасета [CASIA-2](https://www.kaggle.com/datasets/sophatvathana/casia-dataset).
Локальное использование возможно с помощью Predict.ipynb с заменой image_name на название изображения, которое необходимо проверить.
Ссылка на файл модели: https://disk.yandex.ru/d/4NAZXIeoAJt-yQ

This project on image compression artifacts using ELA (Error Level Analysis) allows you to determine the facts of editing with visualization of the verification results and a probabilistic assessment of belonging to one of two classes - original or processed. This project has a number of versions, which you can read above. The model with the highest quality indicators is "VG-16, 30 ep, le 1 e4, 2600 CASIA-2". The parameters of this model correspond to its name - it is based on the VGG-16 architecture, training took place in 30 epoch, the dataset consisted of 2600 images of a modified [CASIA-2](https://www.kaggle.com/datasets/sophatvathana/casia-dataset) dataset. Local use is possible with the help of Predict.ipynb with the replacement of image_name with the name of the image that needs to be checked. Link to the model file: https://disk.yandex.ru/d/4NAZXIeoAJt-yQ

![Метрики VGG-16, 30ep, le1e-4, 2600 CASIA-2](https://user-images.githubusercontent.com/109477509/223042660-641d6428-49d5-4be4-928c-59f3b255d00c.jpeg)
