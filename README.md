//palindrome sequence 
#include <iostream>
#include <algorithm>

int main() {
    std::string sequence;

    std::cout << "Enter a sequence: ";
    std::cin >> sequence;

    std::string reversed = sequence;
    std::reverse(reversed.begin(), reversed.end());

    if (sequence == reversed) {
        std::cout << "The sequence is a palindrome." << std::endl;
    } else {
        std::cout << "The sequence is not a palindrome." << std::endl;
    }

    return 0;
}
