

## Aim
To understand and apply arithmetic, logical, miscellaneous, and assignment operators in C++.

## Software Used
- VS Code

## Problem Statements

1. **Boolean Operators in C++**
   - Write a program to demonstrate the use of boolean operators.

2. **Equality Check in C++**
   - Write a program to check if two values are equal.

3. **Inequality Check in C++**
   - Write a program to check if two values are not equal.

## Theory

- **`boolalpha`**: A manipulator that sets the `boolalpha` flag, instructing the stream to read or write boolean values as text according to the stream's locale.

- **Equality Operator (`==`)**: Returns `true` if both operands have the same value; otherwise, it returns `false`.

- **Inequality Operator (`!=`)**: Returns `true` if the operands do not have the same value; otherwise, it returns `false`.




# Program codes
```javascript
//Mukesh Rothe //23070123089 //CDS EXP3
#include <iostream>
using namespace std;
int main ()
{
    int a,b;
    cout<<"Enter the value of a: "<<endl;
    cin>>a;
    cout<<"Enter the value of b:"<<endl;
    cin>>b;
    cout<<"A==B:"<<(a==b)<<endl;
    return 0;
}

//Mukesh Rothe //23070123089 //CDS EXP3
#include<iostream>
using namespace std;
int main(){
    bool a= true;
    bool b= true;
    cout<<boolalpha;
    cout<<"A&&B: "<<(a&&b)<<endl;
    return 0;
}

 //Mukesh Rothe //23070123089 //CDS EXP3
 #include<iostream>
 using namespace std;
 int main()
{
    int a,b;
    cout<<"Enter first number: ";
    cin>>a;
    cout<<"Enter second number: ";
    cin>>b;
    cout<<"A!=B: "<<(a!=b)<<endl;
    return 0;
}

//Mukesh Rothe //23070123089 //CDS EXP3
 #include<iostream>
 using namespace std;
 int main()
{ int a,b;
    
    a = 1;
    b = 1;
    cout<<"A&B: "<<(a&b)<<endl;
    cout<<"A|B: "<<(a|b)<<endl;
    cout<<"A^B: "<<(a^b)<<endl;
    cout<<"~A: "<<(~a)<<endl;
    cout<<"A<<B: "<<(a<<b)<<endl;
    cout<<"A>>B: "<<(a>>b)<<endl;
    
    return 0;
}
```

# Output:
Equality-

![Screenshot 2024-08-22 210451](https://github.com/user-attachments/assets/af071dba-4fb0-4886-917c-da7bf3aa2702)

Boolean-

![Screenshot 2024-08-22 210603](https://github.com/user-attachments/assets/be931ac8-b75f-48a1-b37c-f09967da2b55)

Inequality-

![Screenshot 2024-08-22 210752](https://github.com/user-attachments/assets/f5bd9722-2ce7-4199-af74-9023a73a2a8c)

Operators-

![Screenshot 2024-08-22 210839](https://github.com/user-attachments/assets/7bae79c9-ce47-467c-bb44-e068f71c3c22)


## Conclusion

- We learned how to use various operators in C++ including boolean, equality, and inequality operators.



