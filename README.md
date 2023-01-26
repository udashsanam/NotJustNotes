# Aditya's Notes
## Polymorphism
+ **Compile Time Polymorphism**
  <br> Polymorphism that exist at the time of **Compilation** is called Compile Time Polymorphism. It is also called static polymorphism or early binding. Compile-time polymorphism is achieved by method overloading and operator overloading.
  + **_Method Overloading_** 
  <br> Whenever class contain more than one Method with **SAME NAME BUT DIFFERENT PARAMETER** is called Method Overloading. Method Overloading occurs when a class has many methods with the same name but different parameters. Two or more methods may have the same name if they have other numbers of parameters, different data types, or different numbers of parameters and different data types. 
  <br> For Example: 
    1. void gfg() { ... }
    2. void gfg(int num1 ) { ... }
    3. void gfg(float num1) { ... }
    4. void gfg(int num1 , float num2 ) { ... }  

+ **Run Time Polymorphism**
<br> Polymorphism that exist at the **Run Time/ Time of execution** is called Run time Polymorphism. Run-time polymorphism is achieved by Method Overriding.
  + **_Method Overriding_**
<br> When a method in a subclass has the ***SAME NAME, SAME PARAMETER  & SAME RETURN TYPE(or sub-type) as a method*** in its super-class, then the method in the subclass is said to override the method in the super-class. <br> For Example: <br>
![image](https://user-images.githubusercontent.com/107999400/214625840-b68db069-741c-4d32-8d4c-2d18dad39256.png)




