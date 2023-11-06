#include <iostream>
#include <stdlib.h>
#include <iomanip>
#include <cmath>

using namespace std;

class question1 {
    public:
     void myMethod()
    {
        cout<<"1- Choose default values\n";
        cout<<"2- Choose number of cookies per box\n";
        cout<<"Option: 1\n";
       
        int cib = 24;
        int bip = 75;
        int ck, nob, nbl, nop, npl;
        cout << "\nEnter the number of cookies: ";
        cin>>ck;
       
        nob=ck/cib;
        nbl= ck % cib;
       
        nop=nob/75;
        npl= nob % 75;
       
        cout<<"\nThe number of cookie boxes needed to hold the cookies: "<<nob<<endl;
        cout<<"Leftover cookies: "<<nbl<<endl;
        cout<<"The number of containers needed to store the cookie boxes: "<<nop<<endl;
        cout<<"Leftover boxes: "<<npl<<endl;
       
       
    }
};
   
    class question2 {
    public:
     void myMethod()
    {
        const int bip = 75;
        int ck, cib, nob, nbl, nop, npl;
       
        cout<<"1- Choose default values\n";
        cout<<"2- Choose number of cookies per box\n";
        cout<<"Option: 2\n";



        cout<<"\nEnter the number of cookies: ";
        cin>>ck;
        cout<<"\nEnter the number of cookies in a box: ";
        cin>>cib;
       
        nob=ck/cib;
        nbl= ck % cib;
       
        nop=nob/75;
        npl= nob % 75;
       
        cout<<"\nThe number of cookie boxes needed to hold the cookies: "<<nob<<endl;
        cout<<"Leftover cookies: "<<nbl<<endl;
        cout<<"The number of containers needed to store the cookie boxes: "<<nop<<endl;
        cout<<"Leftover boxes: "<<npl<<endl;
       
    }
};
int main()
{
    int question;

    cout << "Enter your choice [1, 2]?\n";
    cin >> question;

    if (question == 1)
    {
        cout<<"\n";
        question1 myObj;
        myObj.myMethod();
    }
   
    if (question == 2)
    {
        cout<<"\n";
        question2 myObj;
        myObj.myMethod();
    }

    return 0;
}
