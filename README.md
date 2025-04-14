#Kalinka Song Cpp
#include <iostream>
#include <thread>
#include <chrono>

using namespace std;

void kalinka(int repeats) {
    for(int i = 0; i < repeats; i++) {
        std::cout << "Kalinka, kalinka, kalinka moya!\n";
        std::cout << "V sadu yagoda malinka, malinka moya!\n";
    }
}

void chorus(int times) {
    for(int i = 0; i < times; i++) {
        std::cout << "Ay lyuli, lyuli, ay lyuli, lyuli!\n";
    }
}

int main() {
    chorus(1);
    kalinka(1);
    chorus(2);
    kalinka(1);
    chorus(3);
    
    return 0;
}
kalinka
e4r4r
