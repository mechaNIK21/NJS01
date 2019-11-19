# NJS01


## Задание 1.2.
```js
var ticets = 660;
var i = 0, money, cash = 0, attempt = 0;

for (i; i < ticets; i++) {
    money = confirm(`Снять наличные?`)
    if (money) {
        cash += 100;
        attempt += 1;
        console.log(`Твое бабло ${cash} за ${attempt} попыток`)
    if (cash > 700) {
        console.log(`Не хватает денег для снятия`)
        break
        }
    }
    else {
        console.log(`Не хватает монет`)
        break 
        }
    }
```
