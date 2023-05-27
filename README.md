# include <iostream>
int main() { 
    double usd_to_eur = 0.85;  // 1 USD = 0.85 EUR
    double usd_to_gbp = 0.72;  // 1 USD = 0.72 GBP

    double amount;
    std::cout << "Enter the amount in US dollars: ";
    std::cin >> amount;

    double eur = amount * usd_to_eur;
    double gbp = amount * usd_to_gbp;

    std::cout << "Equivalent amount in euros: " << eur << std::endl;
    std::cout << "Equivalent amount in British pounds: " << gbp << std::endl;

    return 0;
}

