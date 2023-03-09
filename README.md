2.
#include<iostream>
#define SIZE 255
using namespace std;
#include <locale.h>
int main()
{
 int arr[SIZE];
 int lot, i = -1;
 
    do{
        i++;
        cout << "введите свое число - ";
        cin >> arr[i];
    }
    while(arr[i] != -1);
 
 int sum = 0;
 for(int j = 0;j < i; j += 1){
     sum += arr[j];
 }
 
 cout << " сум = " << sum << endl;
 
}

1.
using namespace std;
#include <locale.h>
#include<iostream>
int main()
{
 int numb;
 cout << "введите своё число " << endl;
 cin >> numb;
 
 int summa = 0;
 for(int i = -1;i > numb; i -= 2){
     summa += i;
 }
 cout << " сумма = " << summa << endl;
}
                                 
