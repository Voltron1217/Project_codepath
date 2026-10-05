# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
   When i opened up the file. It wanted me to play guessing game. So i enter my guessing number and it gave me a hint saying " go lower" and i did. I kept on going until i reach the lowest number. So thats one bug i notice because it show me the correct number and i was way off. The second thing i notice is that there are different types of level of difficulties so i played each one and i couldnt play anymore. Which is weird. And lastly i believe the most difficulty level "Hard" is not hard.  

- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").
Three bugs i noticed.
1. The hit is giving me the wrong direction of my guessing game
3. Couldn't start a new guessing game 

**Bug Reproduction Log**

Document at least 3 bugs you found. Add rows as needed.

| Input | Expected Behavior | Actual Behavior | Console Output / Error |
|-------|-------------------|-----------------|------------------------|
|Guess of 80 | "Go Lower" hint | "Go Higher" hint | "Go Higher" hint Out of attempts! The secret was 14. Score: -5  and i suspected location for the code is in app.py , check_guess function |
|Couldnt play any difficulty. Guess 10 | "go higher or go lower" | nothing appearing in app.py, line 126 to line 132| Game over. Start a new game to try again. |
| Guess -5| "Choose a number between 1 and 100"| "Go lower" | Out of attempts! The secret was 8. Score: -20 |

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
I use Claude code in my vs-code 
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
# One example Ai suggestion that was correct was when i asked it if these lines of code where the main cause of the game not resetting. But it point to me in a different lines of code and after i reread the code. I actually forgot about those lines of code.  
- Give one example of an AI suggestion you did not accept as written (including what the AI suggested, why you rejected or changed it, and how you verified your version). It does not have to be a suggestion that was wrong: over-engineered, out of scope, harder to read, or a poor fit for this codebase all count.

# One of the suggestion it made was changing the range of random numbers. it wasn't making sense and suggestion to Reactor the entire if statement, but i gave it a logical option as well.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
# i opened up the app.py and tried to run some test and it works. However i saw other bugs that needed to fix so i went back to the files and look through line by line to see if these line of code are good or not. 
- Describe at least one test you ran (manual or using pytest)  
# I test the amount of attempted i can made and if it get reset or not. i was relieve when it worked. Meaning everytime i reset the game. It reset the the attempts i made. 
  and what it showed you about your code.

- Did AI help you design or understand any tests? How?
# AI helped me understand the tests. Because it was showing me everything was working and that i did a newer test in the test_logic file to see if it was working. 
---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
 # That everytime you interact with the website, like clicking buttons or text something inside a text box. It will restart everything and rebuilds the website again. If my friend doesnt get it then i will explain to him on a familar game he played and tell him. 


---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?

  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.

# One habit i want to reuse for future projects is first read the lines of code and tried to understand it and then work with AI. because you need to know what each line does. This could be both the testing havits and prompting stragety because AI doesnt know what you want it to do. and you need it to guide it in the right direction. One thing i will do differently is give it more details. This changes a lot for me when working with AI that generated code. Its kinda easy for me to ask if i am doing it right or wrong and give me a direction on where i should be writing. or replacing my code.




