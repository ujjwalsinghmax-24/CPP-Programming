#include <iostream>
using namespace std;

int main()
{
    double Num1, Num2;
    char Operation;

    cout << "SIMPLE CALCULATOR" << endl;

    cout << "Enter Your First Value : ";
    cin >> Num1;

    cout << "Enter Your Operation [ + , - , * , / ] : ";
    cin >> Operation;

    cout << "Enter Your Second Value : ";
    cin >> Num2;

    double Result;
    bool Valid = true;

    switch (Operation)
    {

    case '+':
        Result = Num1 + Num2;
        break;

    case '-':
        Result = Num1 - Num2;
        break;

    case '*':
        Result = Num1 * Num2;
        break;

    case '/':
        if (Num2 == 0)
        {
            cout << "Error Division By Zero." << endl;
            Valid = false;
        }
        else
        {
            Result = Num1 / Num2;
        }

        break;
    default:

        cout << "Error ! Invalid Operator !" << endl;
        Valid = false;
        break;
    }

    if (Valid)
    {
        cout << "\nResult : " << Num1 << " " << Operation << " " << Num2 << " = " << Result << endl;
    }

    return 0;
}
