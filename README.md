# week17
task 1

Сделайть интерфейс преобразования ФИО на три поля (input). Учесть все нюансы - лишние пробелы, отсутствие больших букв в именах и пр. Например, было введено пользователем "   Цветкова алиса АлександровНА  ", а стало три поля: Имя: Алиса, Фамилия: Цветкова, Отчество: Александровна
![Снимок экрана (64)](https://user-images.githubusercontent.com/79243168/137589843-62913370-db57-44f4-b0f0-40ce8cea4af4.png)
![Снимок экрана (65)](https://user-images.githubusercontent.com/79243168/137589845-f426869b-d750-4220-bc16-13ca2c9c8031.png)

task 3

 Написать функцию `formatDate(date)`, форматирующую `date` по следующему принципу: 
    - Если спустя `date` прошло менее 1 секунды, вывести `"прямо сейчас"`.
    - В противном случае, если с `date` прошло меньше 1 минуты, вывести `"n сек. назад"`.
    - В противном случае, если меньше часа, вывести `"m мин. назад"`.
    - В противном случае, полная дата в формате `"DD.MM.YY HH:mm"`. А именно: `"день.месяц.год часы:минуты"`, всё в виде двух цифр, т.е. `31.12.16 10:00`.
        
        Например:
        
        ```jsx
        alert( formatDate(new Date(new Date - 1)) ); // "прямо сейчас"
        
        alert( formatDate(new Date(new Date - 30 * 1000)) ); // "30 сек. назад"
        
        alert( formatDate(new Date(new Date - 5 * 60 * 1000)) ); // "5 мин. назад"
        
        // вчерашняя дата вроде 31.12.2016, 20:00
        alert( formatDate(new Date(new Date - 86400 * 1000)) );
        ```
![Снимок экрана (69)](https://user-images.githubusercontent.com/79243168/137589893-61d3497a-4e40-44b0-9f01-7bb87c8730ef.png)
![Снимок экрана (70)](https://user-images.githubusercontent.com/79243168/137589894-52a03cdb-b39d-46d1-8324-d545a95a791e.png)
![Снимок экрана (71)](https://user-images.githubusercontent.com/79243168/137589895-5bde32d2-a77c-4749-b7a3-f66add8eb7f5.png)
![Снимок экрана (72)](https://user-images.githubusercontent.com/79243168/137589896-aa4e80c4-24c1-4c10-9e98-2369bc3c3e47.png)

task 4

Сделайте генератор 10 случайных чисел (по нажатию на кнопку) в диапазоне от -10 до 10 и найдите среди них минимальное, максимальное и среднее арифметическое, а также сумму и произведение всех этих чисел. *В этой задаче вам понадобятся массивы и циклы.*

Пример.

*Сгенерировали: -9 1 8 -2 3 2 0 1 -5 7*

*Минимальное: -9*

*Максимальное: 8*

*Среднее арифметическое: 0.6*

*Сумма чисел: 6*

*Произведение чисел: 0*
![Снимок экрана (73)](https://user-images.githubusercontent.com/79243168/137589934-d2e8b27d-0d8e-4e42-a23c-d546c645f2a7.png)
![Снимок экрана (74)](https://user-images.githubusercontent.com/79243168/137589936-1d48a473-f85e-4eb2-b41f-aca95b011eb3.png)
