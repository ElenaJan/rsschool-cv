# Elena Janecek

## Contact information:

* **E-mail**: elena.janecek@gmail.com
* **Telegram**: @ElenaJanPov


## About me

I'm a web designer with a great passion for coding. I want to become a frontend developer. I love frontend because of combining logic and creativity that are important to make a good website.


## Skills

* HTML
* CSS 
* Sass
* JavaScript
* Vue
* Git
* Figma
* Photoshop


## Code example

**Kata from Codewars:** *Digital root is the recursive sum of all the digits in a number. Given n, take the sum of the digits of n. If that value has more than one digit, continue reducing in this way until a single-digit number is produced. The input will be a non-negative integer.*

```
function digitalRoot(n) {
  let result = 0;
  String(n).split('').map(num => {
    result += Number(num);
  })
  return (result < 10) ? result : digitalRoot(result);
}
```

