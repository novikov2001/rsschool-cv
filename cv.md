# This my curriculum vitae
#### My name is Ilya Novikov
---
### Contact me
* lyanovikovn@mail.ru
* [Vk](https://vk.com/id176117791)
### About me
I live in Belarus in the city of Gomel.I strive to start a career as a front-end developer.  
I am persistent and learn fast
### My skills
I have not bad theoretical and practical skills in languages such as:
* HTML
* CSS
* JavaScript
* C#
* C/C++
### Sample code  
Return an array containing the numbers from 1 to N, where N is the parametered value. N will never be less than 1 (in C#, N might be less then 1).  
Replace certain values however if any of the following conditions are met:   
If the value is a multiple of 3: use the value "Fizz" instead
If the value is a multiple of 5: use the value "Buzz" instead
If the value is a multiple of 3 & 5: use the value "FizzBuzz" instead  
```JavaScript
function fizzbuzz(n)
{
  var arr=[];
  for(i=1;i<=n;i++){
    arr.push(i);
    if(arr[i-1]%3==0 && arr[i-1]%5==0){arr.splice(i-1,1,"FizzBuzz")}
    else if(arr[i-1]%5==0){arr.splice(i-1,1,"Buzz")}
    else if(arr[i-1]%3==0){arr.splice(i-1,1,"Fizz")}
  }
  console.log(arr);
  return arr;
}
```
### Education
I am a student of the Belarusian State University of Transport.     
now currently taking JavaScript courses Frontend
### English level
My english level A2-elementary
