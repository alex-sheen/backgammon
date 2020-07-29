# Backgammon | CMSC 15100

Turn-based two player game of Backgammon with dice rolling, hitting, and bearing off capabilities ! Recorded game history with save/load feature as well as an undo button

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Download the `DrRacket` IDE [here](https://download.racket-lang.org).

### Run
1. Clone this repo into your folder of choice.
    ```
    $ git clone https://github.com/alex-sheen/backgammon.git
    ```
2. Open the `backgammon.rkt` file in `DrRacket`.
3. Click **File->Install Package**, then install '2htdp-typed'.
4. Click **Run**.
5. In the `DrRacket` _interactions window_, make the function call `(run STYLE)`, replacing "STYLE" with either 'main-style' or 'test-style'.

### Play
* Once a game is begun, it can be stored by striking the `s` key.
* A previously stored game may be loaded by striking the `l` key. You will need to select a stored-game file for loading.
* Moves within a game may be undone by striking the `u` key.

## Built With
* [DrRacket](https://racket-lang.org/) – IDE for Racket Languages
