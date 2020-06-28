# SOFTWARE REQUIREMENTS SPECIFICATIONS

## DEAL OR NO DEAL

1.	Introduction

..1	Purpose: Recreational and entertainment purposes – a fun game 

..1	Intended Audience: 

...1.	People of any age group (5+)
...1.	Developers
..1	Scope: A website where the game can be played. 
..1	Definitions and Acronyms: 
...1.	Player: the user playing the game
...1.	Banker: computer algorithm that produces optimized offers
2.	Overall Description
..2.	User Needs: 
...2.	A device with internet connectivity
...2.	A Google account
3.	System Features and Requirements
..3	Functional Requirements:
...3.	The player should, initially, be able to sign in or sign up using their Google Account (more accounts to be added later).
...3.	On logging in, the player should be able to start a new game. 
...3.	A game board containing the amounts ranging from $0.01 - $1,000,000 should then be displayed along with 26 cases, and the player should be able to pick a case for himself. 
...3.	The player should then be able to play the first round, i.e., select 6 cases (selecting a case means the cases open and display an amount, which then disappears from the game board). 
...3.1	At the end of the round, the screen should display an incoming phone call from the banker, and which the user should be able to “pick up”.
...3.	The screen should then display the offer made by the banker to buy the player’s case, along with two buttons for “Deal” and “No Deal”, one of which the player should be able to select, thus deciding the future of the game. 
...3.	If the player selects “Deal”, the game should end and a “Congratulations” message should be displayed on the screen. The player should then be given an option to exit or start a new game.
...3.	However, if the player selects “No Deal”, the game should start the second round, repeating the above- mentioned steps, until the player either selects “Deal” or is down to 2 cases, in which instance he should be able to open his own case. 
...3.	The game should then end and a “Congratulations” message should be displayed on the screen. The player should then be given an option to exit or start a new game.



1)	Login screen: Sign in/up using Google account
2)	Welcome Screen: Start a New Game button
3)	Game Board Screen: Game Board containing prize amounts 
4)	Cases Screen: 26 cases (all buttons) that the user should be able to select from
5)	Game Board and Cases Screen: The game board is displayed which functions according to the cases picked by the user.
6)	Single Case Screen: Shows the case picked by the user which then opens and displays the amount inside the case.
7)	Phone Call Screen: Ringing phone call screen, which the user should be able to “answer”.
8)	Choice Screen: Banker’s offer along with two buttons for “Deal” and “No Deal”.
9)	Deal Consequence Screen: Congratulations message
10)	Final Choice Screen: User’s case and the last case should be displayed and the user should be able to open his case.
11)	Final Amount Screen: Prize money and Congratulations message
12)	Last Screen: “Quit” or “Start a New Game” buttons
