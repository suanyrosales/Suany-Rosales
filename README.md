class Car:
    def __init__(self):
        self.num_doors = 0

    def add_door(self):
        self.num_doors += 1

def add_numbers(a, b, c):
    return a + b + c

def main():
    # Calling the add_numbers function
    result = add_numbers(2, 3, 5)
    print("Sum of numbers:", result)

    # Creating a car object
    myCar = Car()

    # Adding a door to the car
    myCar.add_door()

    # Showing the number of doors
    print("Number of doors in myCar:", myCar.num_doors)

# Calling the main function
main()
