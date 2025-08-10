## 🐶 Project 2 — Human Age to Dog Years Converter

This JavaScript program converts a person's **human age** into **dog years**.

---

### 📜 Description
- The first **2 human years** count as **10.5 dog years each**.
- Every year after that counts as **4 dog years**.
- The program calculates and displays your name, human age, and equivalent dog age.

---

### 💻 Code
```javascript
// My age in human years
var myAge = 32; // Age of me

// Early years in dog years
var earlyYears = 2; // First 2 years
earlyYears *= 10.5; // Each early year counts as 10.5 dog years

// Later years in dog years
var laterYears = myAge - 2; // Remaining human years
laterYears *= 4; // Each later year counts as 4 dog years

// Debug output
console.log(earlyYears);
console.log(laterYears);

// Total age in dog years
var myAgeInDogYears = earlyYears + laterYears;

// Name in lowercase
var myName = 'sunil'.toLowerCase();

// Final result
console.log(`My name is ${myName}. I am ${myAge} years old in human years which is ${myAgeInDogYears} years old in dog years.`);
