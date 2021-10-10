# Length-unit-conversion
length=['inches','yards','miles','milimetre','centimetre','metre','kilometre']
feet=float(input("Enter length in feet: \n"))
conv=input("Please enter conversion unit \n")
if conv==length[0]:
  len=feet*12
  print("The length in inches is ",len)
elif conv==length[1]:
  len=3*feet
  print("The length in yards is ",len)
elif conv==length[2]:
  len=feet/5280
  print("The length in miles is ",len)
elif conv==length[3]:
  len=feet*304.8
  print("The length in millimetres is ",len)
elif conv==length[4]:
  len=feet*30.48
  print("The length in centimetres is ",len)
elif conv==length[5]:
  len=feet*0.3048
  print("The length in metres is ",len)
elif conv==length[6]:
  len=feet*0.0003048
  print("The length in kilometres is ",len)
