# OOP Fundamentals

## What is an object?
  - An object is an instance of class.
  - An object is a real world entity that has state and behaviour.
  - An object is also known as runtime entity, because it is created at runtime.

## What is a class?
  - A class is a blueprint of an object.
  ``` 
   class Student{      
        public:        
           string name;
           int id;     
   };                   
   ```
## Constructor and Destructor

- **C++ constructor**
  - Constructor is a special method which is invoked automatically at the time of object creation.
  - It is called constructor because it constructs the values of data members of the class.

  **Types of Constructors**
  - Default Constructor
  - Parameterized Constructor
  ### Default Constructor
  ```
  class Student{
    public:
        int id;
        Student(){  // Default constructor
            id=0;
        }
  };
  ```
  ### Parameterized Constructor
  ```
  class Student{
    public:
        int id;
        Student(int val){  // Parameterized constructor
            id=val;
        }
  };
  ```

- **C++ Destructor**
    -  Destructor destructs the object, it works opposite to the constructor.
    ```
    class Student{
        public:
            int id;
            ~Student(){  // Destructor
                
            }
    };
    ```
## *this* keyword
   - "this" is a keyword that refers to the current instance of the class.
   - **Uses of 'this' keyword**
        - It is used to pass current object as parameter to another method.
        - It is used to refer current class instance variable.
        
## friend function
   - If a function is defined as friend function, then the protected and private data of a class can be accessed using the function.
   - **Declaration**

    ```
    class Student{
            friend findId(string name);
    };
    findId(string name)
    {

    }
    ```

