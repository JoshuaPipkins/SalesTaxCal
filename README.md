# SalesTaxCal
A C++ Program That Calculates Sales Tax Rate. 

#include <iostream>
using namespace std; 
  int main() {
  int saleammount; 
  cout << "Enter the ammount of the sale "; 
  cin >> saleammount;
  cout << "Enter Sale Tax Rate ";
  int saletaxrate; 
  cin >> saletaxrate; 
 int retailsale = saletaxrate*saleammount;
cout << "Amount of sale is: " << saleammount << ".\n";
cout << "Sales Tax is: " << saletaxrate*saleammount << ".\n"; 
cout << "Total Sale: "<< retailsale << ".\n"; 
return 0; 
}
