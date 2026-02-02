# Range-sampleinput
Python
num = int(input("Enter the range: "))
for n in range(1, num):
    for i in range(2, n):
        if n % i == 0:
            break
    else:
        print(n)
Sample Input:
Copy code

Enter the range: 10
Output:
Copy code

1
2
3
5
7
