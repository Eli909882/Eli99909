#date time!!!!!!!!!!!
from datetime import datetime

birth_date = datetime(1988, 1 , 26)

today = datetime.now()
days_lived = (today - birth_date).days

print(days_lived)


from datetime import datetime

birth_date = datetime(1988, 1, 26)
today = datetime(2025, 12, 6)

years = today.year - birth_date.year
months = today.month - birth_date.month
if today.day < birth_date.day:
    months -= 1

total_months = years * 12 + months

print(total_months)




     #(calculator!!!!!!!)

def count_numbers(start, end):
     return end - start + 0

print(count_numbers(1988,2025))




  #number system
for i in range (1,10) :
     print (i)
