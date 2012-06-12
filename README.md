grid-matcher
============

A very simple game idea implemented in Java and uses the Ucigame library(http://www.ucigame.org/)

Rules
  Find the icon that matches the image on the right.
  Your score increases by 50x every time you find a correct
    icon.
  x is your score multiplier.  x increases by 1 every time you
    get 10 icons correct in a row.  When you get an incorrect
    icon, you have to start your count to 10 over again.
  The image on the right changes after 10 seconds, and slowly
    changes faster as more time passes.  Every 20 seconds
    of game time, the 10 seconds decreases by 1.  After it
    is down to 2 seconds, it stops decreasing.
  After you fail to pick the correct image 5 times, the game ends.
  Shoot for the highest score!
