# Kalman  
**Дослідження впливу параметрів**  
1. Матриця коваріації шуму процесу  
При збільшенні значення матриці коваріації шуму процесу фільтр Кальмана більше довіряє вимірюванням і менше передбаченням моделі.  
Q = 1:  
[]()  
Q = 10:  
[]()  
Q = 100:  
[]()
2. Матриця коваріації шуму вимірювання  
У разі збільшення значення матриці коваріації шуму вимірювання знижується довіра до вимірювання, і навпаки, зменшення цього значення робить фільтр Калмана більш чутливим до нових вимірювань.  
R = 1:  
[]()  
R = 10:  
[]()  
R = 100:  
3. Початкова матриця коваріації  
Збільшення призводить до того, що фільтр на початку стає менш впевненим у своєму стані. При зменшенні фільтр більш впевнений у початкових оцінках, тому на початку реакції на зміни будуть повільнішими.  
P = 0,1:  
[]()  
P = 1:  
[]()  
P = 10:  
[]()  
4. Початкова оцінка стану  
Якщо початкова оцінка не відповідає реальному початковому стану, фільтру знадобиться більше часу на коригування. Якщо початкова оцінка близька до реального значення, фільтр швидко стабілізується і буде давати точніші результати від самого початку.  
x = 0:  
[]()  
x = 10:  
[]()  
x = 50:  
[]()  
5. Постійна складова сигналу  
При збільшенні зсуву фільтр зможе адаптуватися до нових середніх значень сигналу, але це може зайняти більше часу. Зменшення зсуву дозволить швидше відстежувати зміни.  
offset = 0:  
[]()  
offset = 10:  
[]()  
offset = 50:  
[]()  
6. Загальний час моделювання  
При збільшенні часу, фільтр має більше часу для стабілізації. Зменшення часу може призвести до того, що фільтр не встигне повністю "налаштуватися", і його оцінки залишаться неточними або нерівномірними.  
total_time = 1:  
[]()  
total_time = 5:  
[]()  
total_time = 0.3:  
[]()  
**Порівняння результатів**  
