# PRODIGY_CS_03
🔐 Password Strength Checker
This is a Python command-line tool that checks the strength of a password based on commonly recommended security criteria. It provides a score, a strength rating, and helpful suggestions for improvement.

📌 Features
Evaluates password based on:

Length (minimum 8 characters)

Presence of lowercase letters

Presence of uppercase letters

Inclusion of digits

Use of special characters

Gives feedback on missing elements

Ranks password strength as:

🔒 Very Strong

✅ Strong

⚠️ Moderate

❌ Weak

▶️ How to Run
Save the file as password_strength_checker.py

Run the script:

bash
Copy
Edit
python password_strength_checker.py
Example interaction:

yaml
Copy
Edit
🔐 Password Strength Checker
Enter a password to check: Hello123

Password Strength: ⚠️ Moderate
Suggestions to improve your password:
❌ Include at least one special character.
✅ Strength Evaluation Criteria
Criteria	Points
At least 8 characters	+1
Contains lowercase letter	+1
Contains uppercase letter	+1
Contains digit	+1
Contains special character	+1

5 points → 🔒 Very Strong

4 points → ✅ Strong

3 points → ⚠️ Moderate

< 3 points → ❌ Weak

