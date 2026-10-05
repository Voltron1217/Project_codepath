# 🎮 Game Glitch Investigator: The Impossible Guesser

## 🚨 The Situation

You asked an AI to build a simple "Number Guessing Game" using Streamlit.
It wrote the code, ran away, and now the game is unplayable. 

- You can't win.
- The hints lie to you.
- The secret number seems to have commitment issues.

## 🛠️ Setup

1. Install dependencies: `pip install -r requirements.txt`
2. Run the broken app: `python -m streamlit run app.py`

## 🕵️‍♂️ Your Mission

1. **Play the game.** Open the "Developer Debug Info" tab in the app to see the secret number. Try to win.
2. **Find the State Bug.** Why does the secret number change every time you click "Submit"? Ask ChatGPT: *"How do I keep a variable from resetting in Streamlit when I click a button?"*
3. **Fix the Logic.** The hints ("Higher/Lower") are wrong. Fix them.
4. **Refactor & Test.** - Move the logic into `logic_utils.py`.
   - Run `pytest` in your terminal.
   - Keep fixing until all tests pass!

## 📝 Document Your Experience

- [ ] Describe the game's purpose.
Its a guessing game. Where you can choose the difficulties of guessing a number between 1 to whatever number it correspond to the level of difficulty. 
- [ ] Detail which bugs you found.
I found couple of bugs when playing with the game. One is everytime i guess the number. It gave me the wrong direction. and goes to the opposite direction. The second bugs is that its not letting play a new game everytime and my attempts are still kept. 
- [ ] Explain what fixes you applied.
The first fix i applied is when it comes to guessing the number and giving me the direction of going up or down. I remove the try-exempt block. The second was adding few lines of code so that it reset everytime i interact with the button "new Game" and resetting my attempts. 

## 📸 Demo Walkthrough

Describe your fixed game in numbered steps so a reader can follow along without watching a video:

1. User enter guess of 50 
2. Game returns "Too high"
3. User enter 25 and return a message of "Too Low"
4. User enter 28 and return a message " Too High"
5. User enter 26 and returns "Correct"

**Screenshot** *(optional)*: <!-- Insert a screenshot of your fixed, winning game here -->

## 🧪 Test Results

```
platform darwin -- Python 3.12.7, pytest-7.4.4, pluggy-1.0.0
rootdir: /Users/voltron1217/project_codepath/Project_codepath
configfile: pytest.ini
plugins: anyio-4.2.0
collected 4 items                                                              

test_game_logic.py ....                                                  [100%]

============================== 4 passed in 0.00s ===============================

```

## 🚀 Stretch Features

- [ ] [If you choose to complete Challenge 4, describe the Enhanced UI changes here — a screenshot is optional]
