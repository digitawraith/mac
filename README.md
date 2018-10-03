#include <iostream>

using namespace std;

int main()
{
    long long int num;
    cout << "Please enter a 10-digits number: ";
    cin >> num;

    cout << "\nThe digits separated:" << endl;

    cout << num/1000000000 << "   " << num/100000000%10 << "   " << num/10000000%10 << "   " << num/1000000%10 << "   " << num/100000%10 << endl;
    cout << num/10000%10 << "   " << num/1000%10 << "   " << num/100%10 << "   " << num/10%10 << "   " << num%10 << endl;

    return 0;
}
