# Bug List

1. Problem: Had to find a way to update text on the page in an alternative way because using document.write replaces everything currently on the page. Solved it by searching for help on the internet and found out that using a text paragraph in html above the script tags could be an alternative.
2. Problem: Need to find a way to make the program recognise which button is the correct one and which is incorrect and process them accordingly. Solved the problem by asking for help from my father who works as a back-end developer and searched the internet for help.
3. Problem: When having both upper and lowercase keys as possible "correct" keys, the program registers pressing shift or caps lock as the "wrong" key thus selecting a new random key to be displayed. Solved by checking if the key pressed is included in the buttons array where all possible "correct" keys are stored.
