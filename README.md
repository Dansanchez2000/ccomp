#include <iostream>

using namespace std;

bool edad(int a){
((a>=18));
}
int main()
{
    cout<<edad(19);
    return 0;
}

int sucesion(int a, int b=1){
    if (b<a){
        cout<<b<<",";
        return sucesion(a,++b);
    }if (b==a){
        cout<<b}
}

int main{
int x,y,z,may,men;
float prom;
prom(5,6,7,may,men,prom);
cout<<may<<endl;
cout<<men<<endl;
cout<<prom<<endl;
}

bool esprim(int n){
 if (n<1
     return false;
 for(int i=2,i<n,i++)
    if(!(n%i))
       return false;
 return true;
}
void esprim(int n){
 intc=0;
 int i=2;
 while(c<n){
        if(esprim1(i)){
            cout<<i<<endl;
            c++;
        i++;
    }
 }
