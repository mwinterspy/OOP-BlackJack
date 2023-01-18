# OOP-BlackJack
My learning process into Object Oriented Programming while I develop a  card game named Black Jack (21) , very popular in Casinos around the world 


Abstraction: Based on how the game works, I indetified these classes and atributes:

    - Player
        . Name
        . Hand
        . Points
        
    - Dealer ( inherits from Player )
        . Baralho
        
After identifying the first classes and atributes i started to build the main menu, using a 'while' loop to choose between all the options. Each options corresponds to a number and depending on the number, the code enters in a specific loop based on the option the user chose.

After creating the menu, I started the game logic. Using  a list to simulate the player's hand, I used the library 'random' to generte a random number between 1 and 13, and then add this number in the list.

A proceeded then to develop the second round, where the player can choose if he wants to continue getting more card, or if he wants to stop and compare the card. I finished with a function that decides de winner based on the sum of the numbers in each list, comparing if they aren less than 21, and wich one of the lists has more points. 


This project was not a big of a deal beacause I was already familiarized with all the concepts used. This was just so I could practice some things that I haven't practiced in a while

