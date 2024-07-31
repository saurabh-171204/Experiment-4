# BITWISE
## AIM
To study and implement C++ Bitwise Operators

## THEORY
Bitwise operators are fundamental tools in computer programming that allow manipulation of individual bits within binary representations of data. Here's a brief overview of the key concepts:

1. Types of bitwise operators:
   - AND (&)

   - OR (|)
   - XOR (^)
   - NOT (~)
   - Left shift (<<)
   - Right shift (>>)

2. These operators work directly on the binary representation of numbers.

3. They are often used for:
   - Efficient memory usage
   - Low-level device control
   - Cryptography and hashing
   - Optimization in certain algorithms

4. Bitwise operations are typically faster than arithmetic operations.

5. They can be used to perform various tasks like setting/clearing specific bits, checking if a number is odd/even, or multiplying/dividing by powers of 2.

## CODE
```

#include<iostream>
using namespace std;
int main(){
    int a,b,a1,a2,a3,a4,a5,a6;

    cout<<"Enter the value for A"<<endl;
    cin>>a;
    cout<<"Enter the value for B"<<endl;
    cin>>b;
    a1=a&b;    //------BITWISE OPERATOR
    a2=a|b;    //------BITWISE OPERATOR
    a3=a^b;    //------BITWISE OPERATOR
    a4=~b;     //------BITWISE OPERATOR
    a5=a<<2;   //------BITWISE OPERATOR
    a6=a>>2;   //------BITWISE OPERATOR

    cout<<"AND of the entered value is "<<a1<<endl<<endl;
    cout<<"OR of the entered value is "<<a2<<endl<<endl;
    cout<<"XOR of the entered value is "<<a3<<endl<<endl;
    cout<<"NOT of B is "<<a4<<endl<<endl;
    cout<<"LEFT SHIFT of A by 2 is "<<a5<<endl<<endl;
    cout<<"RIGHT SHIFT of A by 2 is "<<a6<<endl<<endl;

    return 0;





}
```

# OUTPUT
![image](https://github.com/user-attachments/assets/ad247658-1a50-4519-b0d7-ae12023483d9)


# CONCLUSION

learnt how use bitwise operators in C++.
