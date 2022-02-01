# Hackathon #

# DEFI Loans #

* Current DEFI implementation for loans
  * To get loan you need to give collateral, which is taken in case user didnt payoff loan
  * There are different strategies explored to receive loan withou colateral based on repotation

![image](https://user-images.githubusercontent.com/38141864/152008212-3d2fd765-e9ce-49c1-98b8-ae47d7d2efb9.png)

# Idea for Hackaton #

![image](https://user-images.githubusercontent.com/38141864/152011078-4fc12215-d380-4cd6-a88e-f48877bd14a7.png)


1. Ask for loan
2. Backend process request
3. Backend enables user address to take loan
4. User is taking loan submiting transaction
5. Transaction is process in smart contract, user is approving Smart contract to take installment periodicaly
6. Loan is moved from Smart contract to users wallet
7. Backend calling periodically smart contract for installment
8. Loan is paid back periodically without user interaction
