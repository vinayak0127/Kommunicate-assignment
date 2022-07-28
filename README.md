# Kommunicate-assignment
HTML CSS assignment -> [here](https://vinayak0127.github.io/Kommunicate-assignment/)
### #2
Complete the following javascript function that accepts the url and the parameter
name and returns the value of that parameter.
```

function getUrlParameterValue(url, parameter) {
//Todo: complete this code
}
```
```
let url = "https://www.kommunicate.io/poweredby?utm_source=https://www.kommunicate.io/&utm_medium=webplugin&utm_campaign=poweredby"

function getUrlParameterValue(url, parameter) {
    let param = url.split('?')[1];
    let query = new URLSearchParams(param);

    for (let pair of query.entries()) {
        if (pair[0] === parameter) {
            console.log(pair[1]);
        }
    }
}

getUrlParameterValue(url, "utm_medium");

```
### #3
Write a javascript function that prints the reverse of a number. Example: if the
number is 149, then output should be 941.
```
function reverseNum(n) {
    var digit, result = 0

    while (n) {
        digit = n % 10  //  Get right-most digit. Ex. 123/10 → 12.3 → 3
        result = (result * 10) + digit  //  Ex. 123 → 1230 + 4 → 1234
        n = n / 10 | 0  //  Remove right-most digit. Ex. 123 → 12.3 → 12
    }

    return result
}
```
### #4
Describe the best project you have worked on, including links if any.
```
```
### #5
```
```
