# 💛 JavaScript — основы логики и данных

> 🎓 Учебный мини-гайд по JavaScript: как работать с *операторами, **массивами* и *условиями*.  
> Всё просто, понятно и с примерами кода 👇

---

## 🧮 Операторы — сердце логики

Операторы позволяют выполнять действия над переменными: считать, сравнивать и принимать решения.

```js
let a = 8;
let b = 3;

// Арифметика
console.log(a + b); // ➕ 11
console.log(a - b); // ➖ 5
console.log(a * b); // ✖ 24
console.log(a / b); // ➗ 2.66...

// Сравнение
console.log(a > b);  // true
console.log(a === 8); // true

// Логика
let isActive = true;
let isMember = false;
console.log(isActive && isMember); // false
