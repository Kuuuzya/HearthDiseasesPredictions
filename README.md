Предсказание риска сердечных заболеваний¶
В данной работе я использую машинное обучение для предсказания риска сердечных заболеваний. 
У нас есть файл train.csv с собранными реальными данными о различных показателях, а также о наличии сердечного заболевания. 
Обучив модель на этих данных я предскажу для файла test.csv (с признаками) 
вероятность наличия сердечного заболевания. Оценивать будем с помощью метрики ROC-AUC.

После чего создам приложение с моделью, в котором каждый сможет проверить своё сердце:
https://kuuuzya-demostreamlit-main-iu3w13.streamlit.app