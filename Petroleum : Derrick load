# Derrick-Load calculator
#Wire lines used in Travelling block and Crown Block
n=int(input("Enter number of wire lines: \n " ))
if n==0 or n%2!=0: # wire lines input to be even and positive
 print("Invalid Input \n ")
else :
 if n in range(1,6): # Efficiency of System due to friction 
      e=1
 elif (n==6):
    e=0.876
 elif (n==8):
    e=0.842
 elif (n==10):
    e=0.811
 elif (n==12):
    e=0.782
 elif (n==14):
    e=0.755 
 else :
    e=0.7  
 print("Efficiency: \n",e) 
ds=float(input("Enter drill string weight units kg: \n ")) # Drill string
p=float(input("Enter drill string density units ppg: \n")) # Buoyance string weight
m=float(input("Enter mud density units ppg: \n"))
hk=float(input("Enter hook weight units kg: \n")) # Hook weight
tb=float(input("Enter travelling block weight units kg: \n")) # Travelling block Weight

# Static Derrick Load
# In static condition tension in live and dead line is same
sw=((ds*((p-m)/p)+hk+tb)/n)*(2+n)
# Dynamic Derrick load 
# Under dynamic condition tension in live wire is more than dead wire line
dw=((ds*((p-m)/p)+hk+tb)/n)*(1+e+n)
print("Buoyance Factor: \n", (p-m)/p)
print("Staic derrick load: \n",sw )
print("Dynamic derrick load: \n",dw )
