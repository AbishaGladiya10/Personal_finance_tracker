balance = 0
transactions = []

while True:
    print("\n--- Personal Finance Tracker ---")
    print("1. Add Income")
    print("2. Add Expense")
    print("3. View Transactions")
    print("4. View Balance")
    print("5. Exit")

    choice = int(input("Enter your choice: "))

    if choice == 1:
        amount = float(input("Enter income amount: "))
        balance += amount
        transactions.append(("Income", amount))
        print("Income added successfully!")

    elif choice == 2:
        amount = float(input("Enter expense amount: "))
        balance -= amount
        transactions.append(("Expense", amount))
        print("Expense added successfully!")

    elif choice == 3:
        print("\n--- All Transactions ---")
        for t in transactions:
            print(t[0], ":", t[1])

    elif choice == 4:
        print("\nCurrent Balance:", balance)

    elif choice == 5:
        print("Exiting... Thank you for using the tracker!")
        break

    else:
        print("Invalid choice! Please try again.")
