#include <iostream>
#include <thread>
#include <chrono>

using namespace std;

void displayCake() {
    cout << R"(
               ,   ,   ,
             /       _/|
           /         | ||
        __|  __   __ | ||
       /  | |  | |  || |,__
      |   | |@| |@ || ||  /
      |   |     '   || || /
       \   \__/__\_|| ||/
        \        |  || ||.
         \______ |  || ||
          || || ||  || ||
    )";
}

void cutCakeAnimation() {
    cout << "\n\nCutting the cake";
    for (int i = 0; i < 5; ++i) {
        cout << ".";
        this_thread::sleep_for(chrono::milliseconds(500));
    }
    cout << "\n\n🎂 The cake has been cut! 🎉\n";
}

void revealMessage(const string& name) {
    string message = "Dear Chubby Cheeks,Once again happy birthday. May your year ahead be as sweet as this cake and filled with endless happiness! Keep smiling, It suits you. Never be sad, I'm there for you anytime anywhere. You are a sweet person and continue being that sweet and mad person. I like it. Enjoy your life 🎉✨";
    cout << "\n💌 Special Message: " << message << "\n";
}

int main() {
    string name;

    cout << "🎉 Welcome to the Birthday Wish Program 🎉\n";
    cout << "Enter the name of the birthday person: ";
    getline(cin, name);

    cout << "\n🎂 Displaying a cake for " << name << "...\n";
    displayCake();

    cout << "\n\nPress Enter to cut the cake...";
    cin.get();

    cutCakeAnimation();
    revealMessage(name);

    cout << "\nThank you for using the Birthday Wish Program! 🎊\n";

    return 0;
}
