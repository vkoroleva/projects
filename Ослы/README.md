# Как взвесить осла?

Ослы играют важную роль в сельской местности в Африке. Они нужны людям для перевозки урожая и воды, вспашки полей и для личного транспорта. Когда осел заболевает, ветеринару необходимо выяснить, сколько весит осел, чтобы назначить нужное количество лекарства. К сожалению, у многих ветеринаров в сельской местности, нет возможности возить их в собой специальные весы для взвешивания ослов, поэтому им нужно угадать, сколько весит осел. Вес животного важен для назначения дозы препаратов. Слишком мало лекарства и инфекция может повториться, слишком много лекарств - можно вызвать опасную передозировку. 

В Африке насчитывается несколько миллиона ослов, поэтому важно иметь простой и точный способ оценки веса осла.

Столбцы датасета `train`:
1. BCS - оценка состояния тела: от 1 (истощенный) через 3 (нормальный) до 5 (страдающий ожирением) с шагом 0.5;
2. Age - возраст в годах, младше 2, 2-5, 5-10, 10-15, 15-20, и старше 20 лет;
4. Sex - пол;
5. Length - длинна тела (см);
6. Girth - обхват (по шее в см);
7. Height - высота в холке (см);
8. Weight - вес осла (целевая переменная).

Обхват измеряется вокруг туловища сразу за передними ногами, высота измеряется от земли до того места, где шея соединяется с верхней частью спины, а длина измеряется от переднего локтевого сустава до задней части таза.

Метрика качества `MSE`
