// ======================
// 🌟 ES6_1
// ======================

// 1️⃣ Rewrite code with let and const
const name = "Ayas";
let age = 22;
console.log(Name: ${name}, Age: ${age});

// 2️⃣ Use template literals with variables
const city = "Chennai";
const message = Hello, I am from ${city}.;
console.log(message);

// 3️⃣ Create a function with default parameter values
function greet(person = "Guest") {
  console.log(Welcome, ${person}!);
}
greet();       // Output: Welcome, Guest!
greet("Ayas"); // Output: Welcome, Ayas!


// ======================
// 🌟 ES6_2
// ======================

// 1️⃣ Extract values from an array/object using destructuring
const person = { fullName: "Mohamed Ayas", ageValue: 22, location: "Chennai" };
const { fullName, ageValue } = person;
console.log(fullName, ageValue);

const numbers = [10, 20, 30];
const [first, second] = numbers;
console.log(first, second);

// 2️⃣ Copy an array using spread operator
const arr1 = [1, 2, 3];
const arr2 = [...arr1];
console.log("Copied array:", arr2);

// 3️⃣ Write a function using rest operator
function sum(...nums) {
  return nums.reduce((total, n) => total + n, 0);
}
console.log("Sum:", sum(1, 2, 3, 4)); // Output: 10


// ======================
// 🌟 ES6_3
// ======================

// 1️⃣ Write concise arrow functions
const multiply = (a, b) => a * b;
console.log("Multiply:", multiply(3, 4)); // Output: 12

// 2️⃣ Create a simple class with constructor and method
class Car {
  constructor(brand, model) {
    this.brand = brand;
    this.model = model;
  }

  showDetails() {
    console.log(Car: ${this.brand} ${this.model});
  }
}

const myCar = new Car("Hyundai", "i20");
myCar.showDetails(); // Output: Car: Hyundai i20
