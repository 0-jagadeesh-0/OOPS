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
- 

### **Runtime Polymorphism**
- This type of polymorphism is achieved when the functions are invoked during the runtime.
- It can be achieved by ***function overriding***. 