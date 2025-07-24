# BMI calculator 

weigth = int(input(Write down your weight in KG))
height = int(input(Write down your height in Meter))

Bmi = weight/height**2

if Bmi < 18.5:
 print(`you are underweight`)
elif Bmi <= 24.9:
 print(`healthy weight range`)
elif Bmi >= 25:
 print(`your are overweight`)
else:
print(`Invalid`)