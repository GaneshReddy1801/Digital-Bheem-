# Digital-Bheem-
#Internship at digital Bheem 

H=int(input('Enter your height in Meters: '))
W=int(input('Enter your weight in kilograms: '))
c=W/H**2
print(c)

if c>25:
    print('over weight')
elif 18<c<24:
    print('normal')
else:
    print('under weight')