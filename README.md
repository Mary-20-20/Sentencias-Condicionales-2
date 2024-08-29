# Sentencias-Condicionales-2
Codigo de Sentencias Condicionales en Python

def calc_bmi(height, weight):
    bmi = weight / ((height / 100.0) ** 2)  
    return bmi

height = float(input("Enter your height in cm: "))
weight = float(input("Enter your weight in kg: "))

bmi = calc_bmi(height, weight)

print(f"Your body mass index is {bmi:.2f} kg/m^2")

if bmi < 18.5:
    
    print("You're thin")
elif 18.5 <= bmi <= 24.9:
    
    print("You're in a normal weight")
elif 25.0 <= bmi < 29.9:
   
    print("You're overweight")
else:
   
    print("You're obese")
