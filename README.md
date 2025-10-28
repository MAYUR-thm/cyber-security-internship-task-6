# Task 6 Report: Password Strength Evaluation

## 1. Passwords Created for Testing

# Tool : passwordmeter.com

I created the following five passwords with varying complexity to test.

| Password Number | Password Example      | Characteristics                               |
|-----------------|-----------------------|-----------------------------------------------|
| 1               | `password`            | Common dictionary word, lowercase only.       |
| 2               | `Password`            | Dictionary word with one uppercase letter.    |
| 3               | `P@ssw0rd`            | Common leetspeak substitution.                |
| 4               | `Cat73!`              | Short, but uses multiple character types.     |
| 5               | `Red$ky@7pmInJune!`   | Long passphrase with spaces, symbols, and numbers. |

## 2. Password Strength Test Results

| Password Number | Password Example      | Strength Score / Rating | Feedback from the Tool (Key Points) |
|-----------------|-----------------------|--------------------------|--------------------------------------|
| 1               | `password`            | Very Weak (Score: 4%)    | Deductions for being letters only, consecutive lowercase letters, and repeating characters. Fails minimum requirements. |
| 2               | `Password`            | Weak (Score: 18%)        | Fewer deductions than #1 due to one uppercase letter, but still weak. Deductions for consecutive lowercase letters and repeats. |
| 3               | `P@ssw0rd`            | Good (Score: 56%)        | Meets minimum requirements. Bonus for using 4 character types (upper, lower, number, symbol). Deductions for consecutive lowercase letters and numbers. |
| 4               | `Cat73!`              | Weak (Score: 28%)        | Too short (only 6 characters). Bonuses for using multiple character types are outweighed by the length penalty. |
| 5               | `Red$ky@7pmInJune!`   | Very Strong (Score: 100%) | Excellent length (17 chars). High bonuses for upper/lower case mix, numbers, and multiple symbols. Very few deductions. |

## 3. Key Lessons Learned & Best Practices

Based on the test results, here are the most important factors for creating a strong password:

1.  **Length is Critical:** The most significant factor. Password #5 (`Red$ky@7pmInJune!`) scored 100% largely due to its 17-character length. Password #4 (`Cat73!`), despite having variety, was weak because it was too short.
2.  **Character Variety is Essential:** Using a mix of uppercase, lowercase, numbers, and symbols gives a major bonus. Password #3 (`P@ssw0rd`) achieved a "Good" score because it included all four types.
3.  **Avoid Common Words and Patterns:** Passwords #1 (`password`) and #2 (`Password`) were weak because they are common dictionary words. Simple character substitutions (like `@` for `a` and `0` for `o`) are well-known to attackers and tools, as seen in Password #3, which was only "Good" and not "Strong".
4.  **Use Passphrases:** A string of random words (like Password #5) is long, easy to remember, and very difficult to crack. Adding spaces, symbols, and numbers inside the phrase makes it even stronger.

**Best Practices Summary:**
- Use a **minimum of 12 characters**.
- Create a **random passphrase** (e.g., `BlueCoffee$TableWaves7`).
- Include a **mix of character types** (upper, lower, number, symbol).
- **Never use** dictionary words, pet names, or birthdates.
- Use a **unique password for every account**.

## 4. Common Password Attacks

1.  **Brute Force Attack:** An attacker uses a program to try every possible combination of characters until the password is found. **Long and complex passwords are the best defense**, as they make the number of possible combinations astronomically high.
2.  **Dictionary Attack:** An attacker uses a file containing a list of common words, phrases, and previously leaked passwords. **Avoiding any common word or simple variation (like "P@ssw0rd") is the best defense.**

## 5. Screenshots

The following screenshots from passwordmeter.com show the detailed analysis for each password:
- Screenshot 2025-10-28 210244.png (Password 1: `password`)
- Screenshot 2025-10-28 210341.png (Password 2: `Password`)
- Screenshot 2025-10-28 210416.png (Password 3: `P@ssw0rd`)
- Screenshot 2025-10-28 210450.png (Password 4: `Cat73!`)
- Screenshot 2025-10-28 210528.png (Password 5: `Red$ky@7pmInJune!`)

---

*This report was generated as part of a Cyber Security Internship Task.*
