
# Live Currency Converter Widget

A real-time foreign exchange calculator built with asynchronous JavaScript that fetches live global market rates via a REST API.

## 🚀 Business Features
- **Live Exchange Rates:** Connects to the Frankfurter REST API to convert USD into INR, EUR, GBP, and JPY in real time.
- **Decimal Precision & Input Validation:** Uses `parseFloat()` and `.toFixed(2)` for accurate financial formatting while blocking negative or empty inputs.
- **Resilient Error Handling:** Displays clear loading states and gracefully handles offline network drops using `try / catch`.

## 🛠️ Tech Stack & Concepts Used
- **Semantic HTML5 & CSS3:** Clean mobile-first UI card with responsive form controls.
- **Vanilla JavaScript:** `fetch()` API, `async / await` asynchronous flow, JSON parsing, dynamic object property lookup, and `try / catch` error handling.
