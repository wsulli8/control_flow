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
