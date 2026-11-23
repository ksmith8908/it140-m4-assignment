# it140-m4-assignment
4-3 Assignment: Pseudocode Revisited
Start hilow_game
    DISPLAY Enter the lower bound
    INPUT lowerBound
    DISPLAY Enter the upper bound 
    INPUT upperBound 
    DISPLAY Great, now guess a number between lowerBound and upperBound
    WHILE userGuess != randomNumber
        IF userGuess < randomNumber
        DISPLAY Nope, too low. 
        ELSE userGuess > randomNumber 
        DISPLAY Nope, too high. 
    ENDIF
        userGuess == randomNumber 
        DISPLAY You got it!
END hilow_game
