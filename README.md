# simple-calcu
C++ source code for simple calculator 

#include <iostream>

using namespace std;

int main()

{
//Declare variables for asked values
 float var1, var2;
 char operation;
 float result;

 //prompts user for info,user inputs data
cout << "Calculator" << endl;
cout<< "==================="<< endl<<endl;

cout << "Please enter the first value: " << endl<< endl;
cin >> var1;
cout<< "======================================"<<endl<<endl;
cout << "Please enter the second value: "<< endl;
cin >> var2;
cout << "=============================="<< endl<<endl;
cout << "Please enter the operation required: "<< endl;
cin >> operation;

//if statements for results ,displays results
if ( operation == '+'){
    result = var1+var2;
    cout <<"The sum of  "<< var1<< " and " <<var2<< " is " << result << " ,Thank you"<<endl;
}
else if (operation == '-'){
    result = var1-var2;
    cout <<"The sum of  "<< var1<< " and " <<var2<< " is " << result << " ,Thank you"<<endl;
}
 else if( operation == '*'){
    result= var1*var2;
    cout <<"The sum of  "<< var1<< " and " <<var2<< " is " << result << " ,Thank you"<<endl;

}
else {
    cout << "invalid" << endl;
 }






     return 0;

}




