# 🌟 Website Rating 🌟

This Python script allows users to input details about a website and view the information in a neatly formatted way. It is a simple, beginner-friendly program that demonstrates how to use dictionaries, user input, and string formatting.

## Features
- Input website details such as name, URL, description, and rating.
- Display the collected information in a clean and readable format.

## How It Works
1. The program prompts the user for:
   - The website name.
   - The website URL.
   - A description of the website.
   - A star rating (out of 5).
2. It stores the inputs in a dictionary.
3. The program iterates through the dictionary to print the information in a formatted style.

## Code

```python
print("🌟Website Rating🌟")
print()

name = input("Input the website name: ")
print()
url = input("Input the URL: ")
print()
desc = input("Input your a description: ")
print()
rating = input("Input the stars rating out of 5: ")
print()

dictionary = {"name": name, "url": url, "des": desc, "rating": rating}

for name, value in dictionary.items(): 
    print(f"{name.title()}:{value}")

python```

##Requirements
Python 3.x

##How to Run
Save the script in a file named website_rating.py.
Open a terminal or command prompt.
Navigate to the directory containing the script.
Run the script using the command:
```python
python website_rating.py
python```

##Customization
You can extend the dictionary to include more fields like category, popularity, or launch year.
Enhance the script to validate inputs (e.g., ensure the URL starts with http:// or https://).
##License
This project is licensed under the MIT License - see the LICENSE file for details.

##Contributions
Feel free to submit issues, fork the repository, or suggest new features. Contributions are always welcome!

🌟 Happy Coding!
