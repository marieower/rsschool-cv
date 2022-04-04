Привет! ✌️
Меня зовут Мария Крымова

# Контакты для связи
telegram: @marieower
vk: @marie_ower

# О себе
Студентка первого курса магистратуры университета ВолгГТУ факультета "Информатики и вычислительной техники" кафедры САПР. 
С детства изучаю иностранные языки. Хороший разговорный английский, изучала китайский и итальянский.
В данный момент в активном поиске работы в качестве веб-разработчика.
Есть опыт работы над студенческими проектами кафедр ПОАС и САПР ВолгГТУ сначала в качестве project manager, затем в качестве разработчика веб-интерфейсов. Имеется опыт работы на иностранного заказчика в лице бельгийского университета Thomas More в рамках студенческого обмена в 2019-ом и 2022-ом годах в качестве разработчика веб-интерфейсов.
# Навыки
- JavaScript
- HTML, CSS, БЭМ
- React
- React Native
- Git (GitLab, GitHub)

# Примеры кода
Пара интересных задач с Code Wars:
**Pair of gloves.** Winter is coming, you must prepare your ski holidays. The objective of this kata is to determine the number of pair of gloves you can constitute from the gloves you have in your drawer.
Given an array describing the color of each glove, return the number of pairs you can constitute, assuming that only gloves of the same color can form pairs.
Решение:
```js
function numberOfPairs(gloves) {
  let count = 0;
  let glovesLeft = [...gloves].sort();
  
  while (glovesLeft.length > 1) {
    if (glovesLeft[0] === glovesLeft[1]) {
      count++
      glovesLeft = glovesLeft.slice(2)
    } else {
      glovesLeft = glovesLeft.slice(1);
    }
  }
  return count;
}
```


**My Language Skills.** You are given a dictionary/hash/object containing some languages and your test results in the given languages. Return the list of languages where your test score is at least 60, in descending order of the results.
Решение:
```js
function myLanguages(results) {
  return Object.values(results).filter(val => val >= 60).sort((a, b)=>(b - a)).map(val => getKeyByValue(results, val));
}

const getKeyByValue = (obj, val) => {
  return Object.keys(obj).find(key => obj[key] === val);
}
```

Больше примеров кода в моем репозитории: https://github.com/marieower

# Опыт работы
Студенческие проекты на базе кафедры ПОАС университета ВолгГТУ, 2017-2019.
Использованные навыки:
- ведение документации
- системная инженерия
- дизайн
- тестирование

Проект на базе университета Thomas More, Geel, Belgium, Feb-May 2019
Использованные навыки:
- ведение документации
- системная инженерия
- дизайн
- тестирование
- JavaScript
- HTML, CSS, БЭМ

Студенческие проекты на базе кафедры САПР университета ВолгГТУ, 2021 по настоящее время. 
Использованные навыки:
- React
- React Native
- Code review
- ведение документации
- системная инженерия

Проект на базе университета Thomas More, Geel, Belgium, Feb-May 2022
Использованные навыки:
- ведение документации
- системная инженерия
- дизайн
- тестирование
- React
- styled-components
- React Native
- unit testing
- e2e testing

Ссылка на проект: https://github.com/future-sight-inc/routine-support

# Образование
- высшее "Программная инженерия", ВолгГТУ, 2017-2021, бакалавр
- неоконченное высшее "Информатика и вычислительная техника", ВолгГТУ, 2021-2023, магистр
- стажировка в университете Thomas More University, Applied Computer Science, Geel, Belgium, Feb-May 2019
- стажировка в университете Thomas More University, Applied Computer Science, Geel, Belgium, Feb-May 2022 

# Английский язык
Подтвержденный уровень B2. Проходила языковые курсы в языковом центре "YES" в городе Волгоград с 2007 по 2015. Проходила две студенческие стажировки в Бельгии в 2019 и 2022 соответственно, языком коммуникации являлся английский. Проходила курс английского на базе бельгийского университета Thomas More во время стажировки в 2019.