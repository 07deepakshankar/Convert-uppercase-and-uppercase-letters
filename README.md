# Convert-uppercase-and-uppercase-letters
# Get the input from the user
ch = input("Enter any character:")
if(ch>='A' and ch<='Z'):
    ch = ch.upper()
    print("The entered charater was in uppercase. In lowercase it is:"+ch)
else:
    ch = ch.lower()
    print("The entered character was in lowercase. In uppercase it is:"+ch)
