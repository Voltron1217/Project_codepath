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
|Guess of 80 | "Go Lower" hint | "Go Higher" hint | "Go Higher" hint Out of attempts! The secret was 14. Score: -5  |
|Couldnt play any difficulty. Guess 10 | "go higher or go lower" | nothing appearing | Game over. Start a new game to try again. |
| Switch difficulty| refresh the page| nothing is happening | Out of attempts! The secret was 8. Score: -20 |

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- Give one example of an AI suggestion you did not accept as written (including what the AI suggested, why you rejected or changed it, and how you verified your version). It does not have to be a suggestion that was wrong: over-engineered, out of scope, harder to read, or a poor fit for this codebase all count.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
