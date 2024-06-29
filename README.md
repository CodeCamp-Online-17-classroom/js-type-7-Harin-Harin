# ja-lab-16
### Lab16 Dynamic Type: Guess Result2
จงหาผลลัพธ์ที่เกิดขึ้น
หริณ มาเบ้า มิก

```JavaScript
console.log('' + 1 + 0);
console.log('' - 1 + 0)); 
console.log(true + false);
console.log(6 / '3');
console.log('2' * '3');
console.log('   -9   ' - 5);
console.log('   -9   ' + 5);
console.log('4px' - 2);
console.log(2 + 4 + 'px');
console.log(null + 1);
console.log(undefined + 1);
```
```shell
console.log('' + 1 + 0); = 10
console.log('' - 1 + 0)); = Uncaught SyntaxError: Unexpected token ')'
console.log(true + false); = 1
console.log(6 / '3'); = 2
console.log('2' * '3'); = 6
console.log('   -9   ' - 5); = -14
console.log('   -9   ' + 5); =    -9   5
console.log('4px' - 2); = NaN
console.log(2 + 4 + 'px'); = 6px
console.log(null + 1); = 1
console.log(undefined + 1); = NaN
```
