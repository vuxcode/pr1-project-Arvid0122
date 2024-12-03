# Bug List

1. Problem: Had to find a way to update text on the page in an alternative way because using document.write replaces everything currently on the page. Solved it by searching for help on the internet and found out that using a text paragraph in html above the script tags could be an alternative.
3. Problem: Need to find a way to make the program recognise which button is the correct one and which is incorrect and process them accordingly. Solved the problem by asking for help from my father who works as a back-end developer and searched the internet for help.

4. Problem: When having both upper and lowercase keys as possible "correct" keys, the program registers pressing shift or caps lock as the "wrong" key thus selecting a new random key to be displayed. Solved by checking if the key pressed is included in the buttons array where all possible "correct" keys are stored.
5. Problem: Want to add a colored background area where text will be. Solved: used a div, adjusted the size and changed the background color. Also learned how to push it behind all other elements using "position" and z-index.
6. Problem: When the text telling the user what key to press disappears, all text under moves up and then down when the text reappears again, making everything jump up and down when playing the game. Solution: Made a div with the text in it and set it in a fixed position.
