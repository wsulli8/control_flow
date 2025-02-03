# control_flow
"Initial commit - Control Flow and Functions Challenge Setup."
// ...existing code...

// Declaring a variable purchaseAmount with a value
let purchaseAmount = 150; // Example value

// Applying a discount if the amount is greater than $100
let discount = 0;
if (purchaseAmount > 100) {
    discount = 0.1 * purchaseAmount; // 10% discount
}

let finalAmount = purchaseAmount - discount;
console.log(`Final amount after discount: $${finalAmount}`);

// ...existing code...
// Using template literals for a cleaner approach
let welcomeMessageTemplate = `Hello ${customerName}, welcome to our store!`;
console.log(welcomeMessageTemplate)
// Declaring a login status
let isLoggedIn = true;

// Checking access conditions
if (isLoggedIn) {
    console.log("Access granted.");
} else {
    console.log("Access denied.");
}

// Logical operations
let hasPermission = true;
console.log("Full access:", isLoggedIn && hasPermission);
console.log("Partial access:", isLoggedIn || hasPermission);
console.log("Negated login:", !isLoggedIn);

// Declaring an array sales with at least five sales figures
let
// Using a for loop to calculate the total sales
let totalSales = 0;
for (let i = 0; i < sales.length; i++) {
    totalSales += sales[i];
}

// Logging the total sales to the console using a template literal
console.log(`Total sales: $${totalSales}`); sales = [120, 85, 200, 150, 90];
