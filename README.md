# Largest-of-three-numbers

## Aim:
To write a C# program to find the largest of three numbers

## Algorithm:

### Step1: 
Start
### Step2:
Create a class and declare three variable with integer datatype
### Step3:
Use if condition to check whether num1 is largest than num2 and num3
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3
### Step5:
Use else condition to display that third variable is largest among all the variables
### Step6:
stop

## Program:
```python
using System;
namespace largestnum
{
    class Jay
    {
        static void Main(string[] args)
        {
            int num1, num2, num3;
            
            num1 = Convert.ToInt32(Console.ReadLine());
            num2 = Convert.ToInt32(Console.ReadLine());
            num3 = Convert.ToInt32(Console.ReadLine());
            
            if(num1 > num2 && num1 > num3)
            {
                Console.WriteLine("The Largest Number is " + (num1));
                
            }
            
            else if(num2 > num1 && num2 > num3)
            {
                Console.WriteLine("The Largest Number is " + (num2));
                
            }
            else
            {
                Console.WriteLine("The Largest Number is " +(num3));
                
            }
            
        }
        
    }
    
}

```
## Output:

![image](https://user-images.githubusercontent.com/74660507/187962514-ca9280fd-ccca-4e45-af48-e9624157be44.png)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully
