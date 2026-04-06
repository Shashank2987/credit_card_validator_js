💳 Credit Card Validator (JavaScript)

A fast and lightweight JavaScript application that validates credit card numbers using the Luhn Algorithm, detects card issuers, and performs basic BIN (Bank Identification Number) analysis.

This project demonstrates how the same core validation logic can be implemented in JavaScript (Node.js / Browser).

🚀 Features
✅ Validates card numbers using the Luhn Algorithm
🏦 Detects major card networks:
Visa
MasterCard
American Express
RuPay (optional if implemented)
🔍 Extracts BIN (first 6 digits)
⚡ Works in:
Node.js (CLI)
Browser (if you added UI)
🧪 Test-ready with sample card numbers
🧠 How It Works
1. Luhn Algorithm
Starting from the right, double every second digit
Subtract 9 if result > 9
Add all digits
If total % 10 === 0 → Valid card
2. Issuer Detection
Card Type	Starting Digits	Length
Visa	4	13,16
MasterCard	51–55	16
American Express	34, 37	15
RuPay	60, 65, 81, 82	16
3. BIN (Bank Identification Number)
First 6 digits of the card
Used to identify issuing bank/network
🛠️ Tech Stack
Language: JavaScript
Runtime: Node.js (or Browser)
Tools: VS Code