## JS
### Loops
####  for loop
---
 for loopi iteratsiya qilish uchun ishlatiladi va uni ikki xil usulda ishlatish mumkin
 
 1. Sonlar iteratsiyasi:
 

      ![alt text](image.png)
 2. array yoki object elementlari iteratsiyasi yani


      ![alt text](image-1.png)

---
#### while loop
---
while loopi berilgan condition false ga teng bulguniga qadar looping qiladi

![alt text](image-2.png)

example:

![alt text](image-3.png)
---
### Functions
Function js da ma'lum bir vazifani bajarish uchun yozilgan procedure hisoblanadi va uni biz bir xil procedure larni takror ishlatishni oldini olgani ishlatamiz

![alt text](image-4.png)

![alt text](image-5.png)

#### Function 3 xil xolatda define qilish mumkin:
* function expression

    Bu turdagi function lar define qilinishi bilanoq run qilishni boshlaydi, va function               declaration  dan farqi function name tashlab ketib anonymous function yaratish mumkin
    ![alt text](image-6.png)

* function declaration
    
    Malum bir nom uchun biriktirilgan function hisoblanadi
    ![alt text](image-7.png) 

* arrow function

     Bu turdagi function lar function ichidagi procedure lar kam bulgan vaqtda va return value function call bulgandayoq qaytarilganda ishlatiladi

     ![alt text](image-8.png) 



### Arrays

#### About Array
---
Primitive data type bulib birdan ortiq data ni saqlash uchun ishlatiladi

`const cars = ["Saab", "Volvo", "BMW"];`

va ular bunday define qilinadi:

`const array_name = [item1, item2, ...];`

Ularning type i object hisoblanadi

---
#### Array Methods
---
`arr.length` bu method orqali array length i aniqlanadi

`arr.push(a)` bu method orqali array ning oxiriga yangi element qushiladi

`arr.pop` bu method orqali array oxiridagi element uchiriladi

`arr.shift()` bu method orqali array boshidagi element uchiriladi

`arr.unshift(a)` bu method orqali array boshiga yangi elemet qushiladi

---
### Objects

object uzidagi malumotlarga ularga berilgan nom bilan access qilish imkoniyatini beradi

`const person = {firstName:"John", lastName:"Doe", age:46};`

![alt text](image-9.png)

ular function, object va array type larini ham uzida saqlashlari mumkin.

`person.firstname;`
orqali object elementi chaqiriladi.