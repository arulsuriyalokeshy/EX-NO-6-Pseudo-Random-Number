# EX-NO-6-Pseudo-Random-Number

## AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

## ALGORITHM:
1.Start the program and import the required libraries.<br>
2.Seed the random number generator using the current time(i.e) rand(time(0));<br>
3.Get the number of randon number to generate.<br>
4.Pass the value for number of iterations and print the numbers.<br>
5.End the program.

## PROGRAM:
```
import random

def main():
    count = int(input("Enter the number of random numbers to generate: "))
    min_val = int(input("Enter the minimum value: "))
    max_val = int(input("Enter the maximum value: "))

    print("Pseudorandom numbers:")
    for _ in range(count):
        random_number = random.randint(min_val, max_val)
        print(random_number, end=' ')

if __name__ == "__main__":
    main()
 ```
## OUTPUT:


![image](https://github.com/user-attachments/assets/0f43afae-fdd7-4f1c-ab7a-ac8305e75979)


## RESULT:
Thus the Implementation of Pseudorandom Number Generation Using Standard library was executed
 successfully.
