# code
compilation of programming codes
Height=float(input("Please provide your height in centimeters: "))
Weight=float(input("Please provide your Weight in Kg: "))
Height = Height/100
BMI=Weight/(Height*Height)
print("Your Body Mass Index is: ",BMI)
if(BMI>0):
	if(BMI<=16):
		print("You are significantly underweight")
	elif(BMI<=18.5):
		print("You are underweight")
	elif(BMI<=25):
		print("You are Healthy")
	elif(BMI<=30):
		print("You are overweight")
	else: print("You are significantly overweight")
else:("enter valid details")
