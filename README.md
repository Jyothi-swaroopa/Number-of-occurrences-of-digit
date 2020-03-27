# Number-of-occurrences-of-digit

#include <iostream>

#include <iomanip>

#include <conio.h>

 

using namespace std;

 

int main()

{

    int n,a,digit,cnt,rem;

    cout<<"Enter a number"<<endl;

    cin>>n;

    cout<<"Enter digit to search"<<endl;

    cin>>digit;

    cnt=0;

    a=n;

    while(a>0)

    {

        rem=a%10;

        if(rem==digit)

           {

            cnt++;

           }

        a=a/10;

    }

    cout<<"Number of occurances is" << cnt << "of digit" << digit <<"of number"<<n<<endl;

    getch();

    return 0;

}

 

