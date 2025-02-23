# Rekha-Feb-21-Python-Assignment-
Python assignment on Basics of python which includes datatypes, operators and conditional statements 

name = "Bunny"
age = 21
is_student = False
grades = [85, 90, 78, 92]
average_grade = sum(grades) / len(grades)
favorite_colors = ("blue", "green", "purple")
person_info = {"name": "Alice", "age": 30, "city": "New York"}

if age >= 18 and not is_student:
    print(f"{name} is an adult and not a student.")
elif age < 18 or is_student:
    print(f"{name} is either a student or a minor.")
else:
    print(f"{name}'s status is unknown.")

if average_grade > 80:
    print(f"{name}'s average grade is above 80: {average_grade}")
    if 90 <= average_grade <= 100:
      print(f"Excellent grades {name}!")
    elif 80 <= average_grade < 90:
      print(f"Good grades {name}!")
else:
    print(f"{name}'s average grade is below 80: {average_grade}")

if "blue" in favorite_colors:
    print(f"{name}'s favorite color is blue.")
else:
  print(f"{name}'s favorite color is not blue.")

if "city" in person_info and person_info["city"] == "New York":
    print(f"{name} lives in New York.")
else:
    print(f"{name}'s city is unknown or not New York.")

if age >= 25 and average_grade > 85 and "green" in favorite_colors:
    print(f"{name} meets all criteria.")
else:
    print(f"{name} does not meet all criteria.")

if is_student == True:
    print("The person is a student")
else:
    print("The person is not a student")

if len(grades) > 3:
    print(f"{name} has more than 3 grades.")
else:
    print(f"{name} has 3 or fewer grades.")

if age > 20:
  if average_grade > 90:
    print("Mature student with excellent grades")
  else:
    print("Mature student.")
else:
  print("student is young")

if 100 not in grades:
  print("No perfect grade")
else:
  print("Perfect grade achieved")
  
