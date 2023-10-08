### program 1
```cpp
#include<iostream>
using namespace std;
int main(){
int password;
cout<<"Enter the password: "<<endl;
cin>>password;
while(password<999999){
cout<<"The password does not meet required conditions, please enter the password again"<<endl;
cin>>password;
}
cout<<"The user has now entered a correct password"<<endl;
}
```
### program 2
```cpp
#include<iostream>
using namespace std;
int main(){
int password;
do{
cin>>password;
}while(password<999999);
}
```
### program 3
```cpp
#include<iostream>
using namespace std;
int main(){
while(1){
cout<<"chocaltes";
}
}
```
### program 4
```cpp
#include<iostream>
using namespace std;
int main(){
int count=0;
while(1){
cout<<"chocaltes";
count++;
if(count>100) break;
}
}
```
### program 5
```cpp
#include<iostream>
using namespace std;
int main(){
int i;
for(i=0; ;i++){
cout<<i<<" ";
if(i>100) break;
}
}
```
