# Monthly Household Consumption & Savings Analysis
# Economics Application using inputs, lists, for-loop and while-loop

months = ["January", "February", "March", "April", "May", "June"]

income = int(input("Enter monthly income: "))

expenses = []
savings = []

i = 0
while i < len(months):
    expense = int(input(f"Enter expense for {months[i]}: "))
    expenses.append(expense)
    savings.append(income - expense)
    i += 1

total_savings = 0
for s in savings:
    total_savings += s

average_savings = total_savings / len(savings)

print("\nMonth-wise Economic Summary:")
for i in range(len(months)):
    print(months[i], "- Expense:", expenses[i], "Savings:", savings[i])

print("\nTotal Savings:", total_savings)
print("Average Monthly Savings:", average_savings)
