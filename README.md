#include <iostream>

using namespace std;

int main()
{
    unsigned int num,x1,x2,x3,x4,x5;
    unsigned int y1,y2,y3,y4,y5;
    cout << "Please enter a 10-digit number: ";
    //cin >> num;
    num = 6234567890;

    cout << "\nThe digits separated:" << endl;

    x1 = num/1000000000;
    x2 = num/100000000%10;
    x3 = num/10000000%10;
    x4 = num/1000000%10;
    x5 = num/100000%10;
    cout << x1 << "\t" << x2 << "\t" << x3 << "\t" << x4 << "\t" << x5 << endl;

    y1 = num/10000%10;
    y2 = num/1000%10;
    y3 = num/100%10;
    y4 = num/10%10;
    y5 = num%10;
    cout << y1 << "\t" << y2 << "\t" << y3 << "\t" << y4 << "\t" << y5 << endl;


    return 0;
}
