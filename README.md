# BANK-APP
echo "# BANK-ACCOUNT" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:Bella010997/BANK-ACCOUNT.git
git push -u origin main
The code doesn't run at all, I need to made some changes to improve it.
class Bankaccount() :

   accountNum= int(input("Please insert your account no.: "))

   accountName = input("Please insert the account name: ")

   deposit = 0

def account(self):

       self.number= accountNum

       self.name = accountName  

       self.balance = deposit
print("\n\n\n The Account has been created! ")

def implementAccount(self):

       print("AccountNum: ", self.number)

       print("AccountName: ", self.name)

       print("Account Balance:",self.balance)
  
def modifyAccount(self):

       print("Account Number : ",self.number)

       self.name = input("Modify My Account Name :")


       self.balance = int(input("Modify My Balance :"))
def deposit(self, amount):
  amount = float(input("Enter amount to be Deposited:"))
  if amount <= 0:
    print("Your account has 0.0 dollars on it.") 
    return 
  else: 
    print(f"The amount deposited was {amount}")
    self.balance += amount
    self.show_balance()
def balance():
  amount = deposite
  total += amount
  balance -= amount
  print(f'Your balance is {balance}')

def deleteAccount(num):
  
  os.remove(account)
  
def modifyAccount(num):

  print (user.account)
user.update()

character =''
num=0

while character != 8:

   #system(“cls”);

   print("A ) Welcome to ")

   print("B ) Create Account")

   print("C ) Deposit")

   print("D ) Withdraw Ammount")

   print("E ) Delete an account")

   print("F ) Modify an account")

   print("G ) Exit")

   print("Select Your Option (A-G) ")

   character = input()

   #system(“cls”);  

   if character == 'A':

     implementAccount(self);

   elif character =='B':

       num = int(input("Enter your account No. : "))
       print("Amount Deposited:",amount)

   elif character == 'C':

       num = int(input("Enter your account No. : "))

      
   elif character == 'D':
     
    num = int(input("Enter your account No. :"))

   elif character == 'E':

       num =int(input("\tEnter your account No. : "))

       deleteAccount(num)

   elif character == 'F':

       num = int(input("\tEnter your account No. : "))

       modifyAccount(num)

   elif character == 'G':

       print(" Bye!")

       break

   else :

       print("Character not found, Please try again!")  

   



