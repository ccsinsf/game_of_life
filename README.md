Below is our standard take-home test to assess a candidate's ability to understand, debug, and fix someone else's (bad) code. (Not that we have bad code here!)

Please send what you have after 90 minutes. (If you're close, feel free to spend another 30 minutes on it.) If you have any questions or get stuck, please email/call me. I'll be standing by.

Instructions:
Life is a simple cellular automata program. It has these rules:
* Cells are either alive or dead,
* All the cells are laid out on a rectangular grid (WHICH WRAPS AROUND THE EDGES),
* Each cell has 8 neighbors. For example : cell (2,2) has the neighbors : (1,1) (1,2) (1,3) (2,1) (2,3) (3,1) (3,2) (3,3)
* If you board is wrapping correctly cell (0,4) has the neighbors : (0,3) (1,3) (1,4) (1,5) (0,5) (xsize - 1,3) (xsize -1,4) (xsize-1,5)
* If a dead cell has exactly 3 living neighbors it becomes alive in the next generation
* If a living cell has exactly 2 or 3 living neighbors it stays alive in the next generation, otherwise it dies

Someone has tried to write a version of the Life program in JavaScript, but hasn't had time to make it work right yet. So far it can setup and draw the grid (in text) which shows the 1st generation of cells. A click of a 'next' link tries to transform and draw the grid in the 2nd generation of cells by applying the above rules, but it fails!

Make it work! All three of the provided BoardSetups (declared in life broken.html) should work according to the rules listed above. To view the boards ("flower", "blinker", and "glider") working correctly, please open each. (*They were provided in a zip file)

Notes:
- When submitting your response, please name the file(s) like this: 'firstname_lastname_v1.html'. If you submit more than one version, the second filenames should contain 'v2', etc.
- You can compare your code's output to the working solutions and document the areas of your program that are not working correctly.
