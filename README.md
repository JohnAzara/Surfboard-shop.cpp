# Surfboard-shop.cpp
// John Azara Surfshop.cpp.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include <iostream>
#include <string>

int main()
{
    std::cout << "Hello World!\n";
}

int iTotalSmall = 0;
int iTotalMedium = 0;
int iTotalLarge = 0;

std::string option_selection;

   while (true)
{
    cout << �Please enter selection �;
    cin >> option_selection;
    transform(option_selection� lowercase

        if (option_selection == �t�)
            DisplayPurchase(iTotalSmall, iTotalMedium, iTotalLarge)
}

system(�pause�);
return 0;
// A function to sell surfboards.
Void MakePurchase(int& iTotal XXXS, iTotalSmall, iTotalMeduim, iTotal Large) // Int& basically returns the variable without return statement.
{
    cout << �Please enter the quantity and type(XXXS = squirrel, S = small, M = medium, L = large) of surfboard you like to buy : �;
    // Initializing variables
    int surfboard_quantity = 0;
    string surfboard_size;
    // Input
    cin >> surfboard_quantity >> surfboard_size;
    transform(surfboard_size.begin(), surfboard_size.end(), surfboard_size.begin(), tolower); // Lowercase
    cout << "\n"
        // Add to variables( respective size and quantity) depending on user input
        if (surfboard_size == �xxxs�)
            iTotalXXXS += surfboard_quantity;
        else if (surfboard_size == �s�)
            iTotalSmall += surfboard_quantity;
        else if (surfboard_size == �m�)
            iTotalMeduim += surfboard_quantity;
        else if (surfboard_size == �l�)
            iTotalLarge += surfboard_quantity;
    // To buy a surfboard press �P�
        else if (selection_input == �p�)
        {
            MakePurchase(iTotalXXXS, iTotalSmall, iTotalMedium, iTotalLarge); // Executes function
        }
    // To display the current purchase press �C�
        else if (selection_input == �c�)
    {
        DisplayPurchase(iTotalXXXS, iTotalSmall, iTotalMedium, iTotalLarge); // Executes function
    }
    To display the current purchase press �T�
        else if (selection_input == �t�)
        {
            DisplayPurchase(iTotalXXXS, iTotalSmall, iTotalMedium, iTotalLarge); // Executes function
        }



}
// Run program: Ctrl + F5 or Debug > Start Without Debugging menu
// Debug program: F5 or Debug > Start Debugging menu

// Tips for Getting Started: 
//   1. Use the Solution Explorer window to add/manage files
//   2. Use the Team Explorer window to connect to source control
//   3. Use the Output window to see build output and other messages
//   4. Use the Error List window to view errors
//   5. Go to Project > Add New Item to create new code files, or Project > Add Existing Item to add existing code files to the project
//   6. In the future, to open this project again, go to File > Open > Project and select the .sln file
