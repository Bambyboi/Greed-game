# Greed
Greed is a game in which the player seeks to gather as many falling gems as possible. The game continues as long as the player wants more! 

![image](https://www.google.com/search?q=gems+and+rocks&rlz=1C1ASUM_enWS923WS923&sxsrf=APq-WBuIDApYFDTw1fW6CikIqDGf8QWPiQ:1645847334532&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjJruqNu5z2AhUOUGwGHeO5DusQ_AUoAXoECAEQAw&biw=1366&bih=568&dpr=1#imgrc=nylOM1XzPXS4nM)

## Getting Started

---

## Run the program using Visual studio code. Then open the greed folder and open the _main_.py file and click the run button and see the result.


## Project Structure

---

The project files are organized as follows:

```
+-- greed               (It holds all files)
  +-- data              (inserted all data for the game)
    +-- messages.txt    (let the veiwers of what they have found)
  +-- game              (It holds files that is need to make the game run perfectly)
    +-- casting
      +-- __pycache__   (cache)
      +-- actor.py      (A visible, moving object that takes part in the game. Actor's will maintain track of its identity, location,
                         and speed in two-dimensional space.)
      +-- artifact.py   (An Artifact's will implement sending a message for each gems and rocks.)
      +-- cast.py       (A gathering of actors, the duty of a cast is to keep on eye of a collection of actors. It does adding, 
                         removing and getting them by a group name.)
    +-- directing
      +-- __pycache__   (cache)
      +-- director.py   (It receives directional input from the keyboard and implement it to the robot.)
    +-- services
      +-- __pycache__   (cache)
      +-- keyboard_service.py (The duty of a KeyboardService is to detect player repond on the keyboard and convert them into a 
                         point representing a direction.)
      +-- video_service.py (Outputs the game state. The duty of the class of objects is to draw the game state on the screen.)
    +-- shared
      +-- __pycache__   (cache)
      +-- color.py      (A color. The duty of Color is to hold and provide information about itself. Color has a few methods for comparing 
                         them and converting to a tuple.)
      +-- point.py      (A distance from a relative origin (0, 0). The responsibility of Point is to hold and provide information 
                         about itself. Point has a few convenience methods for adding, scaling, and comparing them.)
  +-- __main__.py     (The main use to gather all information and make them run together.)
+-- README.md         (general info)
```

## Required Technologies

---

- Python 3.8.0

## Authors - Samuel Kaleopa Assignment- I did all by myself I've been contacting my group but no one reply
