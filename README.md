# Experiment---15 

#### Aim 
To study and implement Recursion. 

#### Software 
Visual Studio Code 

#### Theory 

#### Code 

(A) <br> 
```
// NAME - SHLOKA PATEL 
// PRN - 23070123120 
// EXPERIMENT - 15(A) 

#include<iostream> 
using namespace std;

// Creating a function. 

int fact(int n){
    if(n<=1){
        return 1;
    }
    else{
        return(n*fact(n-1));  // Recursion 
    }
}

int main(){
    int X,n;
    cout<<"Enter a number: ";
    cin>>n;
    X=fact(n);
    cout<<X;
    return 0;
}
```

(B) <br> 
```
// NAME - SHLOKA PATEL  
// PRN - 23070123120 
// EXPERIMENT - 15(B) 

#include<iostream> 
using namespace std;

int add(int n){
    if(n<=1){
        return 1;
    }
    else{
        return(n+add(n-1));
    }
}

int main(){
    int X,n;
    cout<<"Enter a number: ";
    cin>>n;
    X=add(n);
    cout<<X;
    return 0;
}
```

(C) <br> 
```
// NAME - SHLOKA PATEL 
// PRN - 23070123120 
// EXPERIMENT - 15(C) 

#include<iostream>
using namespace std;      

// Creating function. 
void reverse(char *str)
{
    if(*str)  // Base Condition 
    {
        reverse(str+1);  // Recursion 
        cout<<("%c",*str);
    }
}

int main() 
{
    char a[50];
    cout<<"Enter a string: ";
    cin>>a;
    reverse(a);  // Function calling 
    return 0; 
}       
```

(D) <br> 
```
```

#### Output 

(A) <br>       
![]() 

(B) <br> 
![]() 

(C) <br> 
![]() 

(D) <br> 
![]() 

#### Conclusion 
I learnt about recursion in C++ and performed programs based on that.  
