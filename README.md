## Experiment - 9: Pointers 

### Title of the Experiment  
Pointers Basics  

---

### Aim  
To study and implement C++ pointer basics.  

---

### Tools Used  
- **Visual Studio Code**  
- **C++ Compiler (g++)**  
- **Operating System:** Windows or Linux  

---

### Theory  
- **Pointers** are symbolic representations of memory addresses.  
- They enable programs to simulate **call-by-reference** and to create and manipulate **dynamic data structures**.  
- Iterating over elements in arrays or other data structures is one of the main uses of pointers.  
- A pointer must always point to a variable of the **same data type** (e.g., `int*` for integers, `char*` for characters).  
- The operator `&` (address-of) gives the address of a variable, and the operator `*` (dereference) is used to access the value stored at that address.  

---

### Algorithms  

#### **Algorithm 1: Pointer with Arrays**  
1. Start  
2. Declare and initialize an integer array `ar` with values `{10, 20, 30}`.  
3. Print the first element of the array using pointer dereference `*ar`.  
4. Declare a pointer `ptr` and initialize it with the base address of `ar`.  
5. Loop from `i = 0` to `i < 3`:  
   - Print the value pointed by `ptr` using `*ptr`.  
   - Increment the pointer `ptr` to move to the next element in the array.  
6. Stop  

#### **Algorithm 2: Pointer Arithmetic with int, float, char**  
1. Start  
2. Declare an integer variable `b = 10` and an integer pointer `ptr`.  
3. Assign `ptr = &b`. Print value of `b`, address of `b`, and dereferenced pointer value `*ptr`.  
4. Increment `ptr` and print its new value.  
5. Declare a float variable `a = 8.923` and a float pointer `n`.  
6. Assign `n = &a`. Print value of `a`, address of `a`, and dereferenced pointer `*n`.  
7. Increment `n` and print its new value.  
8. Declare a char variable `c = '#'` and a char pointer `ch`.  
9. Assign `ch = &c`. Print address of `c` using `ch`.  
10. Increment `ch` and print its new value.  
11. Stop  

---

### Conclusion  
Pointers are special variables that store the **memory address** of another variable. Instead of holding a direct value (like `10` or `'c'`), they hold the location where the value is stored. This allows for **direct memory manipulation**, call-by-reference, and implementation of advanced data structures (like linked lists, trees, and graphs).  

Pointer arithmetic also shows how memory addresses change according to data type sizes (`int` → 4 bytes, `float` → 4 bytes, `char` → 1 byte). This expe
