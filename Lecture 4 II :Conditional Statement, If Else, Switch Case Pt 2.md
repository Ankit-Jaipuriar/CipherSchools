### Program 1
```cpp
#include<iostream>
using namespace std;
int main(){
float a;
cin>>a;
if(a>0.01){
cout<<"The Condition in if statement is correct";
}
}
```
### Program 2
```cpp
#include<iostream>
using namespace std;
int main(){
float a,b;
cin>>a>>b;
if(a>0.01 && b>a){
cout<<"The Condition in if statement is correct";
}
//if(a>0.01 || b>a){
cout<<"The Condition in if statement is correct";
}
else{
cout<<"condition is false";
}
```
### Program 3
```cpp
#include<iostream>
using namespace std;
int main(){
int marks;
cout<<"Student, please enter score to calculate grade";
cin>>marks;
if(marks>90){
cout<<"A";
}
else if(marks<90 && marks>80 ){
cout<<"B";
}
else if(marks<80 && marks>70){
cout<<"C";
}
else(marks<70){
cout<<"Passs"
}
}
```
### Program 4
```cpp
#include<iostream>
using namespace  std;
int main(){
int a,b,c;
cout<<"Give three integers  as input: a, b, c"<<endl;
cin>>a>>b>>c;
if(a>b && c>d){
cout<<"haha";
}
if(a>b && c<d){
cout<<"hehe";
}
else if(a<b && c>d){
cout<<"huhu";
}
}
```
### program 5
```cpp
#include<iostream>
using namespace  std;
int main(){
int a;
cout<<"enter a integer a";
cin>>a;
switch(a)
case 1:
cout<<"The value of a is 1";
break;
case 2:
cout<<"The value of a is 2";
break;
case 3:
cout<<"The value of a is 3";
break;
default:
cout<<"default value will always be printed";
break;
}
```
