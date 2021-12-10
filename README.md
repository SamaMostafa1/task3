# task3
**Uses of Const keyword:**

* Used with Constant Variables
>Ex:
const int number=10;
>
>(The value of integer number=10 can’t be changed)

* Used with pointer variable point to a constant value.
>Ex:
>const int * ptr=&result;
       result=20;
> 
>(Result value can’t change)

* Used with constant pointer variable point to a value
    >int *const ptr=&result;
    >
   > (Pointer (ptr) is constant can’t be changed).


* Used with constant pointer pointing to a constant variable
>Const int *const ptr=&result;
(Result value and pointer (ptr) both are constant can’t be changed)

* Used with const-function Declaration
>const void pop () {
 //code of the function
  }
> 
>int main () {
> 
>pop ()
> 
 >}
>

* Used with const member function of the class.
>class LinkedList {
>int y;
> 
> public:
> 
>void push () const
> 
>{
//code of function
> 
>}
}

*  const return type

* Const function parameters.
>void print (const int y) {
> 
>cout<<y<<endl;
> 
>}
> 
>int main () {
> 
>y=10;
> 
>num=5;
> 
>print(num);
> 
>}

**Uses of & key word:**
*	(address) operator produce a pointer to its operand.
>EX:  Ptr=&number;
* a reference declarator in addition to being the address operator
>Ex:
> 
 >int result;
> 
>int &result= number; // result is a reference to an integer. // The reference is initialized to refer to number. 
 >
>void function(int*& ptr); // ptr is a reference to a pointer

* with overloaded functions only in an initialization or assignment where the left side uniquely determines which version of the overloaded function is used.

* Used with bitwise AND
>EX:
>
>int main (){
> 
>int num1=2, num2=4;
> 
>int result;
> 
>c=num1&num2;
> 
>cout<<”result= ”<<result<<endl;
> 
>}
* Used with logical AND
> EX:
> 
>int main (){
> 
>int num1=3,num2=7;
> 
>While(num1<1&&num1>num2){
> 
>cout<<”number2  greater than number1 and 1 ”<<endl;
> 
>}
> 
>cout<<” condition is false” <<endl;
> 
>}
