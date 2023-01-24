# Kuznetsov Ivan
## Contacts:
    * phone: +7 (953) 953 0356
    * email: mrjohnny@mail.ru
    * tg: causenetsoff
    * discord: somebody#6576

I am an automation engineer for 10 years, my job is related to industrial equipment. I write algorithms for controllers (Step7), set up various types of equipment.
I have been interested in IT for a long time and want to change the field of activity. I like front end and want to make it my profession.
I have some knowledge and basic programming skills in languages such as C++, Java script, dabbled a bit in html.

### My recent JS code (calculating the sum of all elements of an array without limiting their values)
```javascript
// elements of arr could be a strings
const sum = (arr) => {
        if (arr.length == 0) { return 0}
        arr.sort((a, b) => b - a)
        let maxElementLength = arr[0].length
        let total = ''
        let acum = 0
        for (i = 0; i < maxElementLength; i++){
            arr.forEach((element, index) => {
                digit = element.slice(element.length - 1 - i, element.length - i)
                if (digit === '') {arr[index] = ''}
                acum += Number(digit)
            });
            total = String(acum % 10) + total
            acum = Math.trunc(acum / 10)
            if (acum > 0) {total = String(acum) + total}
        }
        console.log(total)
        return total
    }
```

**Education**: higher technical, computer-aided design systems
**English level**: pre-intermediate

[My CV](https://github.com/cause-net-s-off/rsschool-cv/cv "Some info about myself")

