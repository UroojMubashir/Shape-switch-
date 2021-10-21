#include <iostream>
int main()
{
	{
        int sides;
        std::cout << "Please enter number of sides: ";
        std::cin >> sides;

        switch (sides) {
        case 3:
            std::cout << "Triangle has " << sides;
            break;
        case 4:
            std::cout << "Square has " << sides;
            break;
        case 5:
            std::cout << "Pentagon has " << sides;
            break;
        case 6:
            std::cout << "Hexagon has " << sides;
            break;
        case 7:
            std::cout << "Heptagon has " << sides;
            break;
        case 8:
            std::cout << "Octagon has " << sides;
            break;
        case 9:
            std::cout << "Nonagon has " << sides;
            break;
        case 10:
            std::cout << "Decagon has " << sides;
            break;
        default:
            std::cout << "Not a valid input.";
        }
	}
	
}
