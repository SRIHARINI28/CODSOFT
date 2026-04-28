mylist = []

while True:
    print("\nMenu")
    print("1 Add")
    print("2 Show")
    print("3 Delete")
    print("4 Exit")

    ch = input("Enter option: ")

    if ch == "1":
        x = input("Enter task: ")
        mylist.append(x)
        print("Added")
    elif ch == "2":
        if mylist == []:
            print("List is empty")
        else:
            print("Tasks are:")
            for i in range(len(mylist)):
                print(i+1, mylist[i])
    elif ch == "3":
        if mylist == []:
            print("dont want to delete anything")
        else:
            for i in range(len(mylist)):
                print(i+1, mylist[i])

            n = int(input("Enter number: "))
            if n >= 1 and n <= len(mylist):
                mylist.pop(n-1)
                print("Deleted")
            else:
                print("false number")
    elif ch == "4":
        print("end")
        break
    else:
        print("Invalid input")
