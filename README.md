 ------------------------------------------------------------------------------
 dir Tanks
 - Построение Нейронной Сети для классификации Танков по 8 классам: Фердинанд, КВ-2, Прист, ПЗ-3, СУ-85, Т-34, Т-90, Тигр.
 - Результат распознавания  = 80% при использовании предобученной модели VGG19 или Resnet50.
 - При построении своей структуры НС со сверточными слоями - результат = 70%
 <br><br>Tanks_My_neural_net.ipynb - собственная сеть на основе ConV2d
 <br>Tanks_Neural_nets_VGG19NasnetmobileResnet50.ipynb - использование предобученных моделей VGG19, Nasnetmobile, Resnet50
 
 -------------------------------------------------------------------------------
 dir Japanese_Rates
- Построение модели регресии для прогнозирования курса японской йены на 7 дней вперед
- Взяты данные за 5 лет с сайта Сбербанка
- Результат показал абсолютную ошибку (MAE) в копейках = 0.41
<br><br>RC_F01_01_2015_T16_06_2020.xlsx - таблица данных курса японской йены за 5 лет
