#include<iostream>
using namespace std;
int main()
{
    double tempreture;
    char temp [100];
    
    cout << "What is your tempreture ";
    cin >> tempreture;
    
    if(tempreture > 98.6)
    {
        cout << "You have tempreture " << endl;
    }
    else
    {
        cout << "You are all right " << endl;
    }
    
    return 0;

}
