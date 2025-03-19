// 1. Where do you write JavaScript?
// JavaScript can be written inside an HTML file using <script> tags or in a separate .js file.
// Example:
// <script> console.log('Hello, JavaScript!'); </script>

// 2. Writing your first JavaScript code
console.log('Hello, World!');

// 3. The difference between window, document, and console
console.log(window); // Represents the browser window
console.log(document); // Represents the HTML document
console.log(console); // Represents the console for debugging

// 4. Finding errors in any code
try {
    unknownFunction();
} catch (error) {
    console.error('Error found:', error.message);
}

// 5. Data types
console.log(typeof 42); // Number
console.log(typeof "Hello"); // String
console.log(typeof true); // Boolean

// 6. Variables
let name = "John";
const age = 25;
var city = "New York";
console.log(name, age, city);

// 7. Concatenation
let fullName = "John" + " " + "Doe";
console.log(fullName);

// 8. Calculation
let sum = 10 + 5;
console.log('Sum:', sum);

// 9. Converting text to numbers
let strNumber = "123";
let convertedNumber = Number(strNumber);
console.log(convertedNumber + 10); // Output: 133

// 10. Different ways to convert text to numbers
console.log(parseInt("42")); // 42
console.log(parseFloat("42.5")); // 42.5
console.log(+"42"); // 42
