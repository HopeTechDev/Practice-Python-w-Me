# 🏋️ Practice-Python-w-Me (Weight Unit Calculator)

--- 

#### 👨‍🎓 As an engineering student, I love going to the gym to stay healthy and fit while balancing my studies.  
#### 💡 So, I thought of creating a program about it — to practice and study Python at the same time!  
#### ⚖️ This program helps me quickly convert weight between kilograms and pounds and gives me a simple health check.

#### 📝 *Note: This is for my personal use, and the numbers used (like the ideal weight) are based on my own chosen limits for what I consider my max “bad weight" (according to my BMI).*

---

## 🚀 Features
- Convert **Kilograms ↔ Pounds** easily  
- Get a **simple health check** based on my personal weight limits  
- Practice project to improve my **Python coding skills**  

---

## 💻 Code
```python
weight = float(input("Enter your weight: "))
unit = input("Input K for kilograms or L for pounds: ")
upper = unit.upper()
LbsToKg = weight * 0.4535
KgToLbs = weight * 2.204


if upper == "K":
    result_1 = KgToLbs
    print(str(round(result_1, 2)) + " lbs")
    
    if result_1 >= 170:
        print("Your weight is above the healthy range. Consider exercising and maintaining a balanced diet.")
    elif result_1 < 170:
        print("Great! Your weight is within a healthy range. Keep it up!")
        
elif upper == "L":
    result_2 = LbsToKg
    print(str(round(result_2, 2)) + " Kg")
    
    if result_2 >= 76:
        print("Your weight is above the healthy range. Consider exercising and maintaining a balanced diet.")
    elif result_2 < 76:
        print("Great! Your weight is within a healthy range. Keep it up!")

```
#### I'll soon upload the jupyter notebook file after I play around with my code some more and add additional features to it.

---

#### 💪 *“Stronger today than yesterday.”*

---
