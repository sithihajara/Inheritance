# Inheritance

## Aim:

To write a C# program to print some messages using hierarchical inheritance

## Algorithm:
### Step 1:
Create a base class Tyre.

### Step 2:
Create two child class.

### Step 3:
Create a constructor in the base class and print a message.

### Step 4:
create a function in child class to print a message.

### Step 5:
Run the program
## Program:
```
Developed by: Sithi Hajara I
Register Number: 212221230102
```
```
using System;
namespace vehi
{
    public class tyre
    {
        public tyre()
        {
            Console.WriteLine("Base class tyre:");
        }
        public virtual void Display()
        {
            Console.WriteLine("tyre");
        }

    }
    public class scooter : tyre
    {
        public scooter()
        {
            Console.WriteLine("for the Scooter");
        }
        public override void Display()
        {
            base.Display();
            Console.WriteLine("scooter");
        }
    }
    public class car : tyre
    {
        public car()
        {
            Console.WriteLine("for the car");
        }
        public override void Display()
        {
            base.Display();
            Console.WriteLine("car");
        }
    }
    public class abc
    {
        static void Main(string[] args)
        {
            car ar = new car();
            scooter sc = new scooter();
            ar.Display();
            sc.Display();

        }
    }


}
```

## Output:
![243305075-0bf6df09-6038-4c6c-9386-675282d23569](https://github.com/MEENA155/Inheritance/assets/94677128/f3892180-bb06-4052-a196-d9390a26af93)


## Result
C# program to print some messages using hierarchical inheritance is implemented successfully.
