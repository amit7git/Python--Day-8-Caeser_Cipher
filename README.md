# Day 8 – Caesar Cipher 🔐

Part of my **100 Days of Python Projects** challenge.

---

## 🚀 Project Overview
The Caesar Cipher is a simple encryption and decryption program that shifts letters in a message by a fixed number of positions in the alphabet.

The user can choose to **encode** (encrypt) or **decode** (decrypt) a message by providing a shift number.  
Non-alphabet characters such as spaces and symbols remain unchanged.

This project helped me understand the fundamentals of classical encryption techniques and function-based program design.

---

## 📚 What I Learned
- Creating and using functions with parameters
- Understanding **positional arguments** and **keyword arguments**
- Using loops to process text character by character
- Applying the **modulo operator** to wrap around the alphabet
- Handling non-alphabet characters without breaking the program
- Building a program that can restart based on user input

---

## 🛠 How It Works
- The program displays a logo at the start
- The user provides:
  - Direction: `encode` or `decode`
  - Text message
  - Shift number
- For encoding:
  - Letters are shifted forward in the alphabet
- For decoding:
  - Letters are shifted backward
- Characters not in the alphabet are added unchanged
- After displaying the result, the user can choose to run the program again or exit

---

## 💡 Code Highlights
- Uses a reusable `caesar()` function for both encoding and decoding
- Converts decoding into encoding logic by reversing the shift value
- Uses `%` (modulo) to prevent index overflow in the alphabet list
- Clean handling of symbols, numbers, and spaces in the input text

---

## ▶️ Example Usage
    Type your message:
    hello world!
    Type the shift number:
    5
    Here is the encoded result: mjqqt btwqi!
    
    Type 'yes' if you want to go again. Otherwise, type 'no'.
    yes
    
    Type 'encode' to encrypt, type 'decode' to decrypt:
    decode
    Type your message:
    mjqqt btwqi!
    Type the shift number:
    5
    Here is the decoded result: hello world!
    
    Type 'yes' if you want to go again. Otherwise, type 'no'.
    no
    Goodbye

---

## ▶️ How to Run
1. Clone the repository  
2. Run the Python file in a terminal  
3. Follow the on-screen prompts to encode or decode a message  

---

## 🌐 Live Demo
https://amit7git.github.io/Python--Day-8-Caeser_Cipher/
