# 🔐 Task 6: Password Strength Evaluation & Security Practices

This task involves evaluating the strength of different passwords using password strength checkers, identifying good practices, and understanding how password complexity affects overall security.

---

## ✅ 1. Passwords with Varying Complexity

| Password            | Complexity                  |
|---------------------|------------------------------|
| `apple123`          | Low (common word + numbers)  |
| `Appl3!23`          | Medium (uppercase + number + symbol) |
| `Y@8v$1pL!u3W`      | High (random, long, mixed)   |
| `Password1`         | Very Weak (common pattern)   |
| `C0mpl3x@#2025!`    | Strong (mixed case, symbols, long) |

---

## ✅ 2. Elements Used in Passwords

| Element    | Example Used        |
|------------|---------------------|
| Uppercase  | A, P, Y             |
| Lowercase  | p, l, e             |
| Numbers    | 123, 2025           |
| Symbols    | @, !, #, $          |
| Length     | Ranges from 8 to 15+ |

---

## ✅ 3. Password Strength Checker Results

| Password         | Cracking Time        | Feedback |
|------------------|----------------------|----------|
| `apple123`       | 0.09 sec             | Very weak — common + sequential |
| `Appl3!23`       | 49.42 sec            | Weak — common + keyboard pattern |
| `Y@8v$1pL!u3W`   | 9 million years      | Excellent — extremely secure |
| `Password1`      | 0 sec                | Very weak — dictionary word |
| `C0mpl3x@#2025!` | 2 months             | Good — secure and complex |

---

## ✅ 4. Best Practices for Creating Strong Passwords

- Use **at least 12–16 characters**
- Combine **uppercase, lowercase, numbers, and symbols**
- Avoid:
  - Common words or names
  - Simple substitutions like `a → @` or `s → $`
  - Reusing old passwords

---

## ✅ 5. Tips Learned from Evaluation

- Longer passwords are **exponentially harder to brute-force**
- Common patterns like `Password123!` are still weak
- Use **passphrases** (e.g., `Taco!Rain7!Mouse$`) for strong and memorable passwords
- Consider using a **password manager** for storage and generation

---

## ✅ 6. Common Password Attack Methods

| Attack Type         | Description                                     |
|----------------------|-------------------------------------------------|
| Brute Force          | Tries every possible combination                |
| Dictionary Attack    | Uses common password/word lists                 |
| Credential Stuffing  | Uses leaked password databases                  |
| Phishing             | Tricks user into giving away password           |
| Keylogging           | Records keystrokes to steal credentials         |

---

## ✅ 7. How Password Complexity Affects Security

- The **more complex** and **longer** a password is, the **more secure** it becomes
- Example:
  - `abc123` → cracked in **seconds**
  - `F4$kR@p9!zXv` → takes **years**
- Protects against:
  - **Brute force**: More combinations to try
  - **Dictionary attacks**: Randomized structure defeats pre-built wordlists

---

## ✅ Summary

Understanding and implementing password complexity is crucial in defending against the most common and effective password attacks. By using strong, unique, and complex passwords, users greatly enhance their online security posture.

---
