#include <iostream>


int main() {
    double num1 = 0;
    double num2 = 0;
    char operation;

    std::cout << "Enter first number ";
    std::cin >> num1;

    std::cout << "Enter sign (+, -, *, /): ";
    std::cin >> operation;

    std::cout << "Enter second number ";
    std::cin >> num2;

    if (operation == '+') {
	    std::cout << "result " << num1 + num2 << std::endl;
    }
    else if (operation == '-') {
	    std::cout << "result " << num1 - num2 << std::endl;
    }
    else if (operation == '*') {
	    std::cout << "result " << num1 * num2 << std::endl;
    }
    else if (operation == '/') {
        if (num2 != 0) {
		std::cout << "result" << num1 / num2 << std::endl;
        } else {
		std::cout << "result" << std::endl;
        }
    }
   

    return 0;
}
