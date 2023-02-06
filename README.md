#include <iostream>
using namespace std;
int main()
{
    float num1, num2;   
    char m;
    cout << "Enter the first number :";
    cin >> num1;
    cout << "Enter secand number :";
    cin >> num2;
    cout << "Enter the Hisbah  (+ or - or *  or /  ) :";
    cin >> m;
    while (m == '+')
    {
        cout << " the Hisba(Add+) is :";
        cout << num1 + num2 << endl;
        break; 
    }
    while (m == '-') 
    {
        cout << " the Hisba(Subtract-) is :";
        cout << num1 - num2 << endl;
        break;   
    }
    while (m == '*') 
    {
        cout << " the Hisba(Multiplication*) is :";
        cout << num1 * num2 << endl;
        break; 
    }
    while (m == '/') 
    {
        cout << " the Hisba(Division/) is :";
        cout << num1 / num2 << endl;
        break; 
    }
    return 0;
}
