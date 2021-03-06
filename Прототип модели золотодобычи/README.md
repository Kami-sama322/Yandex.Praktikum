# <p style="text-align: center;"> Прототип модели для золотодобычи </p>

**В данном проекте мы проведем исследовательский анализ данных добычи и очистки руды для построения модели определяющей коэффициент восстановления золота из руды, для чего изучим процессы на каждом этапе обработки**
    
**Для решения задачи:** 
    - Изучим датасет и проведем предобработку данных
    - Перепроверим правильность расчета эффективности обогащения руды
    - Проведем исследовательский анализ данных по этапам производства
    - Напишем функцию для вычисления итоговой метрики и обучим модели, проанализируем их
    - сделаем вывод по проделаной работе

**Для выполнения проекта использовались библиотеки:**  
- *Pandas*  
- *Numpy* 
- *Sklearn*  
- *Matplotlib*  

**По результатам работы:**  
- после ознакомления с даннымии их предобработки были построены базовые модели и проверена их адекватность на предсказании медианным значением и ДаммиРегрессором;
- применением методов скалирования исходных данных для улучшения обобщаемости моделей было определено, что модель дерева решений лучше остальных прогнозирует долю восстановления золота. Именно с ее помощью было сделано предсказание на представленной тестовой выборке и определено значение sMAPE равное 11,79%.
