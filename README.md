# Week-8

#include <iostream>
#include <vector>
#include <ctime>

using namespace std;

const int NUM_BOATS = 10;
const int START_TIME = 10 * 60; 
const int END_TIME = 17 * 60;   
const double HOUR_RATE = 20.0;
const double HALF_HOUR_RATE = 12.0;

struct Boat {
    bool available = true;
    int returnTime = 0;
    double moneyEarned = 0.0;
    int totalHoursHired = 0;
};

vector<Boat> boats(NUM_BOATS);



int main() {
    // Main program loop
    while (true) {
        int choice;
        cout << "Menu:\n";
        cout << "1. Calculate money for one boat\n";
        cout << "2. Find next available boat\n";
        cout << "3. Calculate total money and report\n";
        cout << "4. Exit\n";
        cout << "Enter your choice: ";
        cin >> choice;

        switch (choice) {
            case 1:
                // Call for task 1
                break;
            case 2:
                // Call for task 2
                break;
            case 3:
                // Call for task 3
                break;
            case 4:
                cout << "Exiting program.\n";
                return 0;
            default:
                cout << "Invalid choice. Please try again.\n";
        }
    }

    return 0;
}

