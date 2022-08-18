# Car_distance_prediction
## Условие задачи
Перед участниками чемпионата стоит задача — разработать алгоритм,
позволяющий определить дистанцию до впереди идущего автомобиля,
используя для этого датасет фотографий автомобилей с разного расстояния.
Впоследствии этот алгоритм может быть использован в системах навигации
для предупреждения об опасном сближении и для контроля за
соблюдением дистанции.
## Описание входных значений
train – набор изображений с автомобилями
train.csv – для каждого изображения из train по названию файла определено
расстояние для автомобиля
test – набор изображений, для которых необходимо определить целевое
значениеМетрика
## Коэффициент детерминации (R2):
$ R2 = 1 - \frac{\sum\limits_{i=1}^n (y_i-\hat{y})^2}{\sum\limits_{i=1}^n (y_i-\bar{y})^2} $
