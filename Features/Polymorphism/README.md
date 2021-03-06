# Polymorphism

## What is polymorphism?
- Polymorphism is derived from two words, i.e, poly and morphism where poly means many and morph means forms.
- When a member function or an object behaves in different manner under different situations, then it can be defined as polymorphism.

## Types of Polymorphism
- Compile time Polymorphism
- Runtime Polymorphism

### **Compile time Polymorphism**
- This type of polymorphism can be achieved during the compile time.
- This compile time polymorphism can be implemented using ***function overloading*** and ***operator overloading***.

**Function Overloading**
- Function overloading is a feature in 
C++ where functions having same name, but different types of parameters can be overloaded. 

        fun(int a,int b);
        fun(double a,double b);
        fun(int a,int b,int c);
        fun(double a,double b,double c);
        
**Operator Overloading**
- Operator overloading is a compile-time polymorphism in which the operator is overloaded to provide the special meaning to the user-defined data type.
- Operator overloading is used to overload or redefines most of the operators available in C++.

### **Runtime Polymorphism**
- This type of polymorphism is achieved when the functions are invoked during the runtime.
- It can be achieved by ***function overriding***. 

**Function Overriding**
- In function overriding, the function of base class gets a new definition in the derived class.
- The function with same name have different definitions in the parent and child class.

        class A{
            void display()
            {
                cout<<"This is parent class.";
            }
        };

        class B: public A{
            void display()
            {
                cout<<"This is child class.";
            }
        }

**Virtual Function**
- A C++ virtual function is a member function in the base class that you redefine in a derived class. It is declared using the virtual keyword.
- It is used to tell the compiler to perform dynamic linkage or late binding on the function.


