# Eligibility-for-Admission

## Aim:
### To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
### Start the program and declare the variables required.

### Obtain the input from the user and read the values.

### Calculate the total marks and check for the conditions.

### Print the required output.

### End the program.

## Program:
```python
using System;

namespace EngineeringAdmission
{
    class Program
    {
        static void Main(string[] args)
        {
            int maths, physics, chemistry;
            Console.WriteLine("Welcome to Engineering Admission Eligibility Checker");

            Console.Write("Enter Math marks: ");
            maths = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter Physics marks: ");
            physics = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter Chemistry marks: ");
            chemistry = Convert.ToInt32(Console.ReadLine());

            int totalMarks = maths + physics + chemistry;

            if (maths >= 65 && physics >= 55 && chemistry >= 50)
            {
                if (totalMarks >= 180)
                {
                    Console.WriteLine("Congratulations! You are eligible for admission.");

                }
                else
                {
                    Console.WriteLine("Sorry, you are not eligible for admission.");

                }
            }
        }
    }
}
```

## Output:
![eligibility](https://github.com/Leann4468/Eligibility-for-Admission/assets/121165979/03d00066-9a15-4ac2-a400-d7b72d2aa15b)

## Result:
### Thus a C# program to find the eligibility for admission to an engineering course is written and executed.

