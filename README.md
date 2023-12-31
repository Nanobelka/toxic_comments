# [Классификация текстов на позитивные и негативные](https://nbviewer.jupyter.org/github/Nanobelka/toxic_comments/blob/main/toxic_comments.ipynb)
Project for [Yandex.Praktikum](https://github.com/Nanobelka/Yandex_Praktikum)

### **Входные данные**

Набор текстов с разметкой о токсичности.

### **Цель**

Создать модель для классификации текстов на позитивные и негативные.

### **Задачи:**  

- проверить качество разметки данных;
- сделать обработку текстов, удалив из них лишнюю информацию (служебные данные, знаки препинания и т. п.);
- построить пайплайн с использованием TfidfVectorizer();  
- учесть в пайплайне возможность обработки дополнительных признаков;
- построить несколько различных моделей;
- выбрать лучшую модель;
- оценить качество моделей по дополнительным метрикам;
- сделать контрольную проверку на тестовой выборке;
- сформулировать рекомендации для дальнейшего развития проекта.

### Примеры визуализаций

Анализ качества модели
![Анализ качества модели: Confusion Matrix](https://github.com/Nanobelka/toxic_comments/blob/main/images/example_1_confusion_matrix.png)
![Анализ качества модели: Class Prediction Error](https://github.com/Nanobelka/toxic_comments/blob/main/images/example_2_class_prediction_error.png)
