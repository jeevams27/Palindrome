# Palindrome
## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### Step 1:
Create a new Class named palindrome.

### Step 2:
Declare two string variables called str and rev.
### Step 3:
Get the input as string from the user.
### Step 4:
Iterate the loop until the value of i is less than the lenght of string.

### Step 5:
Check whether the reverse of the string is equal to the input string.

### Step 6:
When the condition is true display it as a palindrome,otherwise not a palindrome

### Step 7:
End of the Program.
## Program:
```
Developed by: Paul Andrew D
Reg no: 212221230075
```
```c#
using System;
namespace palindrome
{
    class Program
    {
        public static void Main(string[] args)
        {
            string str, rev = "";
            Console.Write("Enter a string: ");
            str = Console.ReadLine();
            for (int i = str.Length - 1; i >= 0; i--)
            {
                rev += str[i];
            }
            if (rev == str)
            {
                Console.WriteLine(str + " is a palindrome");
            }
            else
            {
                Console.WriteLine(str + " is not a palindrome");
            }
        }
    }
}
```
## Output:
![image](https://github.com/Paul-Andrew-15/Palindrome/assets/94279791/7454b1d8-7637-43cd-b96f-e3fa9d8c3ae4)


![image](https://github.com/Paul-Andrew-15/Palindrome/assets/94279791/f0c5812f-51eb-45a8-8bab-42b4eeb757f8)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
