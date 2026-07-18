<!-- AUTOGEN:STATS -->
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Terminal](https://img.shields.io/badge/mac%20terminal-000000?style=for-the-badge&logo=apple&logoColor=white&labelColor=000000)](https://support.apple.com/guide/terminal/welcome/mac) [![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/) [![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/) 

[![📊 Views](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/VuToV-Mykola/goit-js-hw-04/main/assets/db/visitors-badge.json)](https://github.com/VuToV-Mykola/goit-js-hw-04/graphs/traffic)
[![⭐ Stars](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/VuToV-Mykola/goit-js-hw-04/main/assets/db/likes-badge.json)](https://github.com/VuToV-Mykola/goit-js-hw-04/actions/workflows/screenshot-and-visitor.yaml)
[![📦 Size](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/VuToV-Mykola/goit-js-hw-04/main/assets/db/repo-size.json)](https://github.com/VuToV-Mykola/goit-js-hw-04)
[![📄 License](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/VuToV-Mykola/goit-js-hw-04/main/assets/db/repo-license.json)](https://github.com/VuToV-Mykola/goit-js-hw-04/blob/main/LICENSE)

## 📸 Скріншот проекту
![Project Screenshot](./assets/screenshot.png)
<!-- END:AUTOGEN -->

## My Achievements

![Description](./assets/head.jpg)

## My Certificates - Completed Sololearn Course:

![Certification Badge](./assets/certificat.jpg)

[SOLOLEARN](https://www.sololearn.com/certificates/CT-VJXN3HQH)

# JavaScript Homework 04

## Task 1. Product Packaging

**COMPLETE THIS TASK IN THE FILE `task-1.js`**

Write a function `isEnoughCapacity(products, containerSize)` that calculates whether all products will fit in the container during packaging.

The function declares two parameters:

- `products` — an object where keys contain product names and their values are the quantity of these products. For example, `{ apples: 2, grapes: 4 }`.
- `containerSize` — a number, the maximum number of product units that the container can hold.

The function should return the result of checking whether all products will fit in the container. That is, calculate the total quantity of products in the `products` object and return `true` if it is less than or equal to `containerSize`, and `false` otherwise.

Take the code below and insert it after declaring your function to check the correctness of its work. The console will display the results of its calls.

```javascript
console.log(
  isEnoughCapacity({ apples: 2, grapes: 3, carrots: 1 }, 8)
); // true

console.log(
  isEnoughCapacity({ apples: 4, grapes: 6, lime: 16 }, 12)
); // false

console.log(
  isEnoughCapacity({ apples: 1, lime: 5, tomatoes: 3 }, 14)
); // true

console.log(
  isEnoughCapacity({ apples: 18, potatoes: 5, oranges: 2 }, 7)
); // false
```

Leave this code for mentor verification.

### Mentor Review Criteria

- Declared function `isEnoughCapacity(products, containerSize)`
- Calling `isEnoughCapacity({ apples: 2, grapes: 3, carrots: 1 }, 8)` returns `true`
- Calling `isEnoughCapacity({ apples: 4, grapes: 6, lime: 16 }, 12)` returns `false`
- Calling `isEnoughCapacity({ apples: 1, lime: 5, tomatoes: 3 }, 14)` returns `true`
- Calling `isEnoughCapacity({ apples: 18, potatoes: 5, oranges: 2 }, 7)` returns `false`

## Task 2. Calorie Calculation

**COMPLETE THIS TASK IN THE FILE `task-2.js`**

Write a function `calcAverageCalories(days)` that returns the average daily value of the number of calories that an athlete consumed during the week. The function expects one parameter: `days` — an array of objects. Each object describes a day of the week and the number of `calories` consumed by the athlete on that day.

Take the code below and insert it after declaring your function to check the correctness of its work. The console will display the results of its calls.

```javascript
console.log(
  calcAverageCalories([
    { day: "monday", calories: 3010 },
    { day: "tuesday", calories: 3200 },
    { day: "wednesday", calories: 3120 },
    { day: "thursday", calories: 2900 },
    { day: "friday", calories: 3450 },
    { day: "saturday", calories: 3280 },
    { day: "sunday", calories: 3300 }
  ])
); // 3180

console.log(
  calcAverageCalories([
    { day: "monday", calories: 2040 },
    { day: "tuesday", calories: 2270 },
    { day: "wednesday", calories: 2420 },
    { day: "thursday", calories: 1900 },
    { day: "friday", calories: 2370 },
    { day: "saturday", calories: 2280 },
    { day: "sunday", calories: 2610 }
  ])
); // 2270

console.log(
  calcAverageCalories([])
); // 0
```

Leave this code for mentor verification.

### Mentor Review Criteria

- Declared function `calcAverageCalories(days)`
- Calling `calcAverageCalories` with the following array returns `3180`:
  ```javascript
  calcAverageCalories([
    { day: "monday", calories: 3010 },
    { day: "tuesday", calories: 3200 },
    { day: "wednesday", calories: 3120 },
    { day: "thursday", calories: 2900 },
    { day: "friday", calories: 3450 },
    { day: "saturday", calories: 3280 },
    { day: "sunday", calories: 3300 }
  ])
  ```
- Calling `calcAverageCalories` with the following array returns `2270`:
  ```javascript
  calcAverageCalories([
    { day: "monday", calories: 2040 },
    { day: "tuesday", calories: 2270 },
    { day: "wednesday", calories: 2420 },
    { day: "thursday", calories: 1900 },
    { day: "friday", calories: 2370 },
    { day: "saturday", calories: 2280 },
    { day: "sunday", calories: 2610 }
  ])
  ```
- Calling `calcAverageCalories([])` returns `0`

## Task 3. Player Profile

**COMPLETE THIS TASK IN THE FILE `task-3.js`**

The `profile` object describes a user profile on a gaming platform. Its properties store the profile name `username` and the number of active hours `playTime` spent in the game.

```javascript
const profile = {
  username: "Jacob",
  playTime: 300,
};
```

Complete the `profile` object with methods to work with its properties.

- The `changeUsername(newName)` method should accept a string (new name) in the `newName` parameter and change the value of the `username` property to the new one. Returns nothing.
- The `updatePlayTime(hours)` method should accept a number (number of hours) in the `hours` parameter and increase the value of the `playTime` property by it. Returns nothing.
- The `getInfo()` method should return a string in the format `<Username> has <amount> active hours!`, where `<Username>` is the profile name and `<amount>` is the number of game hours.

Take the code below and insert it after declaring your function to check the correctness of its work. The console will display the results of its work.

```javascript
console.log(profile.getInfo()); // "Jacob has 300 active hours!"

profile.changeUsername("Marco");
console.log(profile.getInfo()); // "Marco has 300 active hours!"

profile.updatePlayTime(20);
console.log(profile.getInfo()); // "Marco has 320 active hours!"
```

Leave this code for mentor verification.

### Mentor Review Criteria

- Declared variable `profile`
- The value of the `profile` variable is an object with properties `username`, `playTime`, `getInfo`, `changeUsername`, and `updatePlayTime`
- The value of the `getInfo` property is a function
- The value of the `changeUsername` property is a function
- The value of the `updatePlayTime` property is a function
- The `this` keyword is used to access object properties in its methods
