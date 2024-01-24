[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
* Name:
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer: --------------------------------------- here

#include <iostream>
#include <string>

class Car {
public:
    std::string model;
    int year;
    std::string color;

    Car() : model("Unknown"), year(0), color("Unknown") {}

    Car(std::string m, int y, std::string c) : model(m), year(y), color(c) {}

    void displayDetails() {
        std::cout << "Model: " << model << ", Year: " << year << ", Color: " << color << std::endl;
    }
};

int main() {
    Car myCar("Honda Accord LXP", 2012, "Silver");
    myCar.displayDetails();

    return 0;
}

```

