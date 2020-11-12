# Operator and Loops

## What is a while loop? 

- Need to set condition before entering the loop
- Operation of a wild loop - "enter while loop/text expression/if false exit loop/if true/ move on
- Not until you achieve "x" can you wake up...
- We don't exactly how many times it is going to run
// while loop
// answer
// prompt for the user
// how many guesses are we going to use
// only use while loop if you dont know how many times to prompt them




# What is A for loop?

- We know exactly how many times it is going to run
-

for (let i = 0; i <= 12; i = i + 1) {
    console.log(i * 8);
}

|| = or - only one condition needs to be true for it to work

&& - means both are true

## sample code
function guessingGame(){

let correctAnswer = 34;
let numberOfGuesses = 3;
                                        i++ is the same as i = i + 1
for (let i = 0; i < numberOfGuesses; i = i + 1) {
    let userAnwser = prompt('please enter a number 1-100')
    // I can verify that it is a number
    // verify that it is between 1-100
    if(userAnwser == correctAnswer)
    alert('Correct Answer')
    break;
    // or you can reasign i = 3
} else {
    alert('Sorry, Wrong Anwser')
}
}
// Invoke the prompt
guessingGame();

function askToPlay(){
    // assigning the variable to the promt
    let wannaPlay = prompt('Do you want to play a guessing fame? (yes or no)')
    while(wannaPlay == 'yes')
        guessingGame();
        wannaPlay = prompt ('Do you want to play again? (yes or no)')
        }
    asktoPlay();

    // longer way below
    
    if(wannaPlay == 'no'){
        alert('It would have been a lot of fun')
    } else if (wannaPlay == 'yes'){
        guessingGame();
    }
    }
}