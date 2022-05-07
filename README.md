# Grading-on-marks

## Aim:
To write a c# program to grade the marks.
## Algorithm:
### Step-1: 
Start.

### Step-2:
Create a class and declare one variable with integer datatype

### Step-3: 
Get marks from the User

### Step-4: 
Use if and elif condition to check the grade

### Step-5: 
Print the grade for the given mark

### Step-6: 
Stop
## Program:
```C#
using System;
namespace sandhya
{
    class program
    {
        static void Main(string[] args)
        {
            int marks;
            Console.WriteLine("ENTER THE MARK:");
            marks = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("\nYOUR GRADE :");
            if (marks > 90)
                Console.WriteLine("O GRADE");
            else if (marks > 80)
                Console.WriteLine("A+ GRADE");
            else if (marks > 70)
                Console.WriteLine("A GRADE");
            else if (marks > 60)
                Console.WriteLine("B+ GRADE");
            else if (marks > 50)
                Console.WriteLine("B GRADE");
            else if (marks >= 40)
                Console.WriteLine("C GRADE");
            else
                Console.WriteLine("FAIL");

        }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/75235167/167235516-18fd61da-aa84-4c8e-bb39-2902191ef9da.png)

## Result:
Thus the C# program to grade the marks is executed successfully
