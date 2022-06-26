# Encapsulation

***Encapsulation*** is the process of binding data members and methods of a program together to do a specific job, without revealing unnecessary details.

It can be defined in two different ways:
- **Data Hiding:** The process of hiding unwanted information, such as restricting access to any member of an object.
- **Data Binding:** The process of binding the data members and the methods together as a whole, as a class.

        class Student{
            private:
                int id;
            void setId(int val)
            {
                id=val;
            }
            int getId()
            {
                return id;
            }
        }

## Access Specifiers

**What are Access Specifiers?**

Access Specifiers define how the data members of class can be accessed.

**Types of Access Specifiers**
- **Public** - It can be accessed from outside the class.
- **Private** - It cannot be accessed from outside the class.
- **Protected** - It cannot be accessed from outside the class,but it can be accessed in inherited class. 
