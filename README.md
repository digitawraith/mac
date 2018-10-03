#include <iostream>
#include <iomanip>

using namespace std;

int main()
{
int studentCount, grade;
int A=0, B=0, C=0, D=0;

studentCount = 1;

while (studentCount <=5)
{
    cout << "Enter the marks obtained by student " << studentCount << ":\n";
    cin >> grade;

/*
    if(grade > 80)
    {
        cout << "Student " << studentCount << " obtained grade A" << endl;
        A++;
    }
    else if(grade > 60)
    {
        cout << "Student " << studentCount << " obtained grade B" << endl;
        B++;
    }
    else if(grade > 50)
    {
        cout << "Student " << studentCount << " obtained grade C" << endl;
        C++;
    }
    else
    {
        cout << "Student " << studentCount << " obtained grade D" << endl;
        D++;
    }
    studentCount++;

*/
}

cout << "Grade Distribution" << endl;

cout << "A: " << setw(A+2) << setfill('*') << "\t(" << A << ")" << endl;
cout << "B: " << setw(B+2) << setfill('*') << "\t(" << B << ")" << endl;
cout << "C: " << setw(C+2) << setfill('*') << "\t(" << C << ")" << endl;
cout << "D: " << setw(D+2) << setfill('*') << "\t(" << D << ")" << endl;

/*
cout << "A: ";

while (A != 0)
{
    cout << "*";
    A--;
}
cout << "\nB: ";
while (B != 0)
{
    cout << "*";
    B--;
}
cout << "\nC: ";
while (C != 0)
{
    cout << "*";
    C--;
}
cout << "\nD: ";
while (D != 0)
{
    cout << "*";
    D--;
}
*/


    return 0;
}
