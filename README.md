# GradientBoosting with AdaLoss
## Выполнено:
- Реализация дерева решений для решения задачи регрессии.
- Реализация градиентного бустинга над этими деревьями.
- Уточнение значений в листьях при помощи гессиана. 
- Сравнение качества классификации для бустингов над деревьями глубины 1, 3, 5 c алгоритмом GradientBoostingClassifier из библиотеки sklearn.
## Графики logloss.
(Зеленым помечен 3% интервал от logloss sklearn модели)
- Для depth=1
![alt text](Pictures/depth_1.png)
- Для depth=3
![alt text](Pictures/depth_3.png)
- Для depth=5
![alt text](Pictures/depth_5.png)