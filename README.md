# SA2-ENRIQUE-III

    #include <iostream>
    #include <string>
    using namespace std;

    int main()
    {
    string name;
    int num;
    int fac = 1;
    int expo = 1;
    int pwresult = 1;
    int table = 0;
  

    cout << "Please enter your name: " << endl;
    getline(cin, name);


    cout << "Welcome " << name << "! Please enter a number!" << endl;
    cin >> num;



    //FACTORIAL
    for (int i = 1; i <= num; i++)
    {
        fac *= i;

    }
    cout << "\nThe factorial of " << num << " is " << fac << endl;


    //TABLE
    cout << "\nThe table of " << num << " from 1- 10 \n\n";
    int i = 1;
    do {
        cout << num << "x" << i << "=" << num * i << endl;
        i++;
    } while (i <= 10);



    //EXPONENT

    for (i = 10; i > 5; i--) {
        pwresult = pwresult * num;
    }
    cout << endl << pwresult;
 




    }
