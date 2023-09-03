# placement_prep
### WAP to print hello world
``` #include<iostream>
using namespace std;
int main(){
       cout<<"Hello Aarti!!";
}
```
### WAP a program to check whether a number is  palindrom or not.
``` #include <bits/stdc++.h>
using namespace std;

int main()
{
    int a;
    cin>>a;
    int c=a;
    int b=0;
    while(a!=0){
        b=(b*10) + (a%10);
        a=a/10;
    }
    if(c==b) cout<<"Palindrom"<<endl;
        
    else cout<<"Not Palindrom";

    
    return 0;
}
```
