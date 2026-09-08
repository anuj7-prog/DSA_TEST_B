\# Ans1- 



An algorithm is a step-by-step procedure used to solve a problem.



Two characteristics of a good algorithm:



clear and unambiguous.

efficient in time and memory.



Ans 2 - 

Static: Size is fixed and cannot easily be changed. Example: Array.

Dynamic: Size can grow during program execution. Example: Linked List.

&#x20;       

Ans4-  

Push: an element to the top of the stack.

Pop: Removes an element from the top of the stack.

&#x20;   

Ans5- 



Enqueue: Adds an element of the queue.

Dequeue: Removes an element of the queue.

&#x20;   

Ans6- 



Best case: O(1) — element is found in  first position.

Worst case: O(n) — element is last in position.

&#x20;   

&#x20;   

Ans8- 



A singly linked list is a collection of nodes where each node contains data, to the next node.



Difference:



Array stores elements in continuous memory and usually has a fixed size.

Linked list uses nodes and can grow or shrink dynamically.





Ans9- 



A binary tree is a tree data structure and 

which have nodes with two children.



left and right child





Pattern stars



\#Ans11 

​

n = 5

for i in range(n,0,-1):

&#x20;   print("\*" \*i)





\#Ans12- 



n = 5

for i in range(1,n+1):

&#x20;   print(str(i) \*i)





**#Ans13-**



**n = 4**

**m = 5**

**for i in range(n):**

&#x20;   **for j in range(m):**

&#x20;       **print("\*", end="")**

&#x20;   **print()**



**Coding questions**





**#Ans16-** 



**n = int(input("Enter n: "))**

**total = 0**

**for i in range(1, n+1):**

&#x20;   **total += i**

**print("Sum=", total)**





**#Ans18-** 



**a = int(input("Enter first number: "))**

**b = int(input("Enter second number: "))**

**while b != 0:**

&#x20;   **a, b = b, a % b**

**print("GCD=", a)**





**#Ans19-** 



**a = int(input("Enter first number: "))**

**b = int(input("Enter second number: "))**

**x = a**

**y = b**

**while y != 0:**

&#x20;   **x, y = y, x % y**

**gcd = x**

**lcm = (a \* b) // gcd**

**print("LCM =", lcm)**





**#Ans21 -** 





**arr = \[25, 10, 45, 5, 30]**

**smallest = arr\[0]**

**for i in arr:**

&#x20;   **if i < smallest:**

&#x20;       **smallest = i**

**print("Smallest =", smallest)**





**# Ans23 -**

**arr = \[10, 20, 10, 30, 20, 40]**

**new\_arr = \[]**

**for i in arr:**

&#x20;   **if i not in new\_arr:**

&#x20;       **new\_arr.append(i)**

**print(new\_arr)**







**# Ans25 -** 



**n = int(input("Enter number: "))**

**total = 0**

**for i in range(1, n):**

&#x20;   **if n % i == 0:**

&#x20;       **total += i**

**if total == n:**

&#x20;   **print("Perfect number")**

**else:**

&#x20;   **print("Not a perfect number")**







**# Ans26**



**n = int(input("Enter number: "))**

**for i in range(1, 11):**

&#x20;   **print(n, "x", i, "=", n \* i)**









