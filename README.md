# lecture---11-cipher-school

In this lecture i have leanred about the while loop condition and aslo learned about the break statement aslo learned about diffenece between '=' and '=='. okk now while loop condtion says that if write the condtion in the while loop it will satisfy when the condition is true and when the condtion statisfies and what break statement will do the break statement will do when the condition is statisfied and the loop will the break it stops in simple terms the loop break when the condition statisfied here is an example code 


#include <iostream>
using namespace std;

int main() {
    int i = 0;

    while (true) {  // Infinite loop
        cout << i << endl;
        i++;

        if (i == 5) {  // Break condition
            break;  // Exit the loop when i equals 5
        }
    }

    return 0;
}
