FlapPyBirdEMG
===============

A clone of a flappy bird [clone](https://github.com/sourabhv/FlapPyBird) that can be played with any microphone input. This project is compatible with Backyard Brain's [SpikerBox](https://backyardbrains.com/products/spikerboxBundle).  

How-to (as tested on MacOS)
---------------------------
Additional pip packages such as `pyaudio` may have to be installed too.

1. Install Python 3.x (recommended) 2.x from [here](https://www.python.org/download/releases/)

1. Install [pipenv]

1. Install PyGame 1.9.x from [here](http://www.pygame.org/download.shtml)

1. Clone the repository:

   ```bash
   $ git clone https://github.com/sourabhv/FlapPyBird
   ```

   or download as zip and extract.

1. In the root directory run

   ```bash
   $ pipenv install
   $ pipenv run python flappy.py
   ```

1. Use <kbd>&uarr;</kbd> or <kbd>Space</kbd> key to play and <kbd>Esc</kbd> to close the game.

(For x64 windows, get exe [here](http://www.lfd.uci.edu/~gohlke/pythonlibs/#pygame))

Notable forks
-------------

- [FlappyBird Fury Mode](https://github.com/Cc618/FlapPyBird)
- [FlappyBird Model Predictive Control](https://github.com/philzook58/FlapPyBird-MPC)
- [FlappyBird OpenFrameworks Port](https://github.com/TheLogicMaster/ofFlappyBird)
- [FlappyBird On Quantum Computing](https://github.com/WingCode/QuFlapPyBird)

Made something awesome from FlapPyBird? Add it to the list :)


ScreenShot
----------

![Flappy Bird](screenshot1.png)

[pygame]: http://www.pygame.org
[pipenv]: https://pipenv.readthedocs.io/en/latest/
