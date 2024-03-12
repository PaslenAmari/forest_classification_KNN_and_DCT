# forest_classification_KNN_and_DCT
Классификация датасета лесного массива через KNN и деревья

Дан датасет для классификации. 

Определим один из 7 преобладающих видов деревьев на лесных участках размером 30*30 метров (7 классов). 

В качества признаков даны высота над уровнем моря, расстояния до подземных источников и мест лесных пожаров, один из 4 лесных зон, 40 типов почвы (последние 40 колонок) и др.

Описание данных можно найти на https://scikit-learn.org/stable/datasets/real_world.html#forest-covertypes

![image](https://github.com/PaslenAmari/forest_classification_KNN_and_DCT/assets/106679149/fd07dbe1-a69e-480c-a5f8-07008e9a0275)

Модель KNN

![image](https://github.com/PaslenAmari/forest_classification_KNN_and_DCT/assets/106679149/19fea1b7-c749-4d4b-87aa-c343d2bb3c4d)


Модель DecisionTreeClassifier 

![image](https://github.com/PaslenAmari/forest_classification_KNN_and_DCT/assets/106679149/da8731d2-c84f-4159-b236-a9c35ad335d2)


Метрики

![image](https://github.com/PaslenAmari/forest_classification_KNN_and_DCT/assets/106679149/1003cb24-e13f-4cc8-843c-0524c6bd7918)

Уменьшение размерности

![image](https://github.com/PaslenAmari/forest_classification_KNN_and_DCT/assets/106679149/912cf7b7-aae6-42eb-9b65-6d7591cdc823)


Выводы:

На основании метрик, полученных в проведенном анализе, качество результатов работы моделей для данной задачи классификации показали, что KNN предпочтительнее чем DecisionTree, т.к. метрики по модели выше
