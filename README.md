# **Определение уязвимых групп населения**
### Над решением  работала команда "PandaOne" по заказу "Теплицы Социальных технологий".


В России проживает большое количество людей, и многие из них находятся в тяжелых жизненных условиях. Это социальная проблема нашего государства, требующая решений федерального масштаба. Но как оказывать помощь нуждающимся гражданам централизованно? Как выявлять и решать проблему бедности и социального неблагополучия на уровне регионов России, а не локально? Каким группам населения и в каких регионах России помощь требуется в первую очередь? 
На эти вопросы нам помогут ответить модели машинного обучения, которые дают возможность кластеризовать регионы России и выделить из них наиболее остро нуждающиеся в помощи.

## Задачи:
- кластеризовать регионы России и определить, какие из них наиболее остро нуждаются в помощи бедным/уязвимым слоям населения
- описать группы населения, сталкивающиеся с бедностью
- установить есть ли влияние на уровень бедности в регионе числа детей, пенсионеров и других социально уязвимых групп
- определить, связаны ли уровень бедности/социального неблагополучия с производством и потреблением в регионе

### Гипотеза: 
***Высокий уровень ВРП региона не влияет на уровень благополучия уязвимых слоев населения.***

## Cпособ решения:

1. Поиск и последующее исследование коррелирующих признаков, которые могут быть прямо или косвенно связаны с уязвимыми слоями населения.
2. Кластеризация полученных данных с выделением фактора ВРП региона и без его учета с целью сравнения и подтверждения (опровержения) гипотезы.
3. Выявление наиболее нуждающихся регионов России.

Под уязвимыми слоями населения будем считать группы людей, которые сталкиваются с проблемами, имеющими следующие признаки:

**Проблема детского населения**:

- Детская смертность, чел.
- Рождаемость, чел.
- Доля детей из малоимущих семей.
  
**Проблема жилищных условий**:

- Размер жилой площади в расчете на члена домохозяйства.
  
**Проблема бедности**:

- Среднедушевые денежные доходы, руб.
- Малоимущие трудоспособные, доля %
- Люди ,живущие за чертой бедности, %
- Численность безработных, чел.
  
**Проблема возраста**:

- Малоимущие пенсионеры, доля %
  
**Проблема здоровья и соц поддержки**:

- Число инвалидов, чел
- Заболеваемость у пациентов с диагнозом, установленным впервые в жизни, на 100 тыс человек населения, чел.
- Расходы на социальную политику, %
- Заболеваемость впервые в жизни установленным диагнозом алкоголизма на 100 тыс.  населения, чел.
- Заболеваемость впервые в жизни установленным диагнозом наркомании на 100 тыс.  населения, чел.
  
Данные признаки будем проверять вместе с экономическими показаниями регионов с целью подтверждения или опровержения и гипотезы, и нахождением закономерностей.
  
  
