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
## Задание 2.2.

```js
function validation (inputName, inputPassword, length) {
    
    var inputTag
    var inputPass
    do {
       inputTag = prompt(`Введите ваш логин ${inputName}`)
      
    }
    while  (typeof inputTag, inputPass === 'string' && inputTag.length < length)
    if (inputTag.length < 3){
        console.log(`Incorrect`)
    }
    do {
         inputPass = prompt(`Введите пароль ${inputPassword}`)
    } 
    while  (typeof inputPass === 'string' && inputPass.length < length)
    if (inputPass.length < 6){
        console.log(`Too easy password`)
    }

    return console.log(inputTag, inputPass)
}

validation(name)
validation(password)
```
