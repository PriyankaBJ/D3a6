# D3a6

1) Can you overload a method with same return type.? Explain your answer with proper logic.

The method should be overloaded with the same return type in order to avoid ambiguity. 
For example,
class A{
static int add(int a,int b){return a+b;}
static double add(int a,int b)
{return a+b;
}
}
class B{
public static void main(String[] args){
System.out.println(Adder.add(11,11));//ambiguity
}}
In this when code is compiled it will show error as: 
Overloading3.java:3: error: method add(int,int) is already defined in class A static double add(int a,int b){return a+b;}

To overcome this problem method should be overloaded with the same return type.

2)  Write a program in java using Arrays, that sorts the element in descending order.
