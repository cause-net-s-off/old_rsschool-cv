# **Kuznetsov Ivan**
#### Junior Frontend developer

---
 
### Contacts:
* **Phone:** +7 (953) 953 0356
* **Email:** mrjohnny@mail.ru
* **Telegram:** @cause_net_s_off
* **Discord:** somebody#6576

### Briefly About Myself:
I am an automation engineer for 10 years, my job is related to industrial equipment. My duties at work are: writting algorithms for controllers (Step7), setting up various types of equipment. I also have extensive experience in motion design, visual effects compositing, video editing and image processing.

Information Technology has been my area of interest for a long time and want to change the field of activity. I like front end and want to make it my profession.

### Skills:
- C++ Basics
- Java Script Basics
- Git/GitHub Basics
- VS Code 
- Adobe Suite Strong skills (After Effects, Photoshop, Premiere Pro, Lightroom)
- Nuke

### Java Script code example: 
*Calculating the sum of all elements of an array 'without limiting' their values*
*I represented the elements in the array as strings*
```javascript
const sum = (arr) => {
        if (arr.length == 0) { return 0}
        arr.sort((a, b) => b - a)
        let maxElementLength = String(arr[0]).length
        let total = ''
        let acum = 0
        for (i = 0; i < maxElementLength; i++){
            arr.forEach((element, index) => {
                digit = String(element).slice(String(element).length - 1 - i, String(element).length - i)
                if (digit === '') {arr[index] = ''}
                acum += Number(digit)
            });
            total = String(acum % 10) + total
            acum = Math.trunc(acum / 10)
        }
        if (acum > 0) {total = String(acum) + total}
        return total
    }
```

### Education: 
Higher technical, computer-aided design systems

### English level:
Pre-intermediate


[My CV](https://cause-net-s-off.github.io/rsschool-cv/cv "Some info about myself")

