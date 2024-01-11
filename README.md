# 11.1-Ciphers


## **Objective:**
- Understand the working principles of Caesar and Vigenère ciphers.
- Implement Python functions for encoding and decoding text using these ciphers.

**HINT: Use the modulo operator(%) for coding the both ciphers. In both cases, the modulo operator is vital for ensuring that the shifted indices wrap around the alphabet and do not go beyond the valid range.**

## **Instructions:**

### **Part 1: Caesar Cipher**

[Caesar Cipher Tutorial](https://www.youtube.com/watch?v=fR8rVR72a6o)
1. **Caesar Encryption Function:**
    - Write a Python function named `caesar_encrypt` that takes two parameters: a plaintext string and an integer key.
    - The function should return the encrypted text using the Caesar cipher.
    - Ensure that the function handles both uppercase and lowercase letters.
    - Non-alphabetic characters (numbers, spaces, symbols) should remain unchanged in the encrypted text.

2. **Caesar Decryption Function:**
    - Write a Python function named `caesar_decrypt` that takes two parameters: an encrypted string and an integer key.
    - The function should return the decrypted text using the Caesar cipher.
    - Make sure to handle both uppercase and lowercase letters, and leave non-alphabetic characters unchanged in the decrypted text.

### **Part 2: Vigenère Cipher**

[Vigenere Cipher Tutorial](https://www.youtube.com/watch?v=E352JJ8xv48)

3. **Vigenère Encryption Function:**
    - Write a Python function named `vigenere_encrypt` that takes two parameters: a plaintext string and a keyword.
    - The function should return the encrypted text using the Vigenère cipher.
    - Ensure that the function handles both uppercase and lowercase letters.
    - Non-alphabetic characters (numbers, spaces, symbols) should remain unchanged in the encrypted text.

4. **Vigenère Decryption Function:**
    - Write a Python function named `vigenere_decrypt` that takes two parameters: an encrypted string and a keyword.
    - The function should return the decrypted text using the Vigenère cipher.
    - Make sure to handle both uppercase and lowercase letters, and leave non-alphabetic characters unchanged in the decrypted text.

**Testing:**
- Create test cases to validate the correctness of your functions.
- Test the functions with various inputs, including different keys and plaintexts.

