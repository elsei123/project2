
/* Global Styles */
body {
    font-family: Arial, sans-serif; /* Sets the font family for the entire body */
    margin: 0; /* Removes default margin */
    padding: 0; /* Removes default padding */
    background-color: #f4f4f4; /* Light gray background color */
    color: #333; /* Dark gray text color */
}

/* Header Styles */
header {
    background-color: #4CAF50; /* Green background color */
    color: white; /* White text color */
    text-align: center; /* Centers the text */
    padding: 1em 0; /* Adds padding to top and bottom */
}

/* Main Content Styles */
main {
    max-width: 600px; /* Sets maximum width */
    margin: 5em auto; /* Centers the main content and adds top/bottom margin */
    padding: 10em; /* Adds padding inside the main content */
    background: white; /* White background color */
    border-radius: 100px; /* Rounds the corners */
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.1); /* Adds a subtle shadow */
}

/* Question Styles */
#question {
    margin-bottom: 1em; /* Adds bottom margin */
}

/* Answer Button Styles */
#answers button {
    display: block; /* Makes the button a block element */
    width: 100%; /* Full width button */
    margin: 0.5em 0; /* Adds top/bottom margin */
    padding: 1em; /* Adds padding inside the button */
    background-color: #4CAF50; /* Green background color */
    color: white; /* White text color */
    border: none; /* Removes border */
    border-radius: 4px; /* Rounds the corners */
    cursor: pointer; /* Changes cursor to pointer on hover */
}

/* Answer Button Hover Styles */
#answers button:hover {
    background-color: #45a049; /* Darker green background on hover */
}

/* Next and Restart Button Styles */
#next-button, #restart-button {
    #next-button, #restart-button {
    background-color: #008CBA;
    color: white;
    border: none;
    padding: 1em 5em;
    border-radius: 4px;
    cursor: pointer;
}
}

/* Next and Restart Button Hover Styles */
#next-button:hover, #restart-button:hover {
    background-color: #007bb5; /* Darker blue background on hover */
}


/* Global Styles */
body {
    font-family: Arial, sans-serif; /* Sets the font family for the entire body */
    margin: 0; /* Removes default margin */
    padding: 0; /* Removes default padding */
    background-color: #f4f4f4; /* Light gray background color */
    color: #333; /* Dark gray text color */
}

/* Header Styles */
header {
    background-color: #4CAF50; /* Green background color */
    color: white; /* White text color */
    text-align: center; /* Centers the text */
    padding: 1em 0; /* Adds padding to top and bottom */
}

/* Main Content Styles */
main {
    max-width: 600px; /* Sets maximum width */
    margin: 5em auto; /* Centers the main content and adds top/bottom margin */
    padding: 10em; /* Adds padding inside the main content */
    background: white; /* White background color */
    border-radius: 100px; /* Rounds the corners */
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.1); /* Adds a subtle shadow */
}

/* Question Styles */
#question {
    margin-bottom: 1em; /* Adds bottom margin */
}

/* Answer Button Styles */
#answers button {
    display: block; /* Makes the button a block element */
    width: 100%; /* Full width button */
    margin: 0.5em 0; /* Adds top/bottom margin */
    padding: 1em; /* Adds padding inside the button */
    color: white; /* White text color */
    border: none; /* Removes border */
    border-radius: 4px; /* Rounds the corners */
    cursor: pointer; /* Changes cursor to pointer on hover */
    background-color: #4CAF50;
}

/* Correct Answer Button */
#answers .correct {
    background-color: #4CAF50; /* Green background color */
}

/* Incorrect Answer Button */
#answers .incorrect {
    background-color: #f44336; /* Red background color */
}



/* Next and Restart Button Styles */
#next-button, #restart-button {
    background-color: #008CBA; /* Blue background color */
    color: white; /* White text color */
    border: none; /* Removes border */
    padding: 1.5em 3em; /* Adds more padding */
    border-radius: 4px; /* Rounds the corners */
    cursor: pointer; /* Changes cursor to pointer on hover */
    display: block; /* Makes the button a block element */
    margin: 2em auto; /* Centers the button horizontally and adds top margin */
    font-size: 1.2em; /* Increases font size */
}

/* Next and Restart Button Hover Styles */
#next-button:hover, #restart-button:hover {
    background-color: #007bb5; /* Darker blue background on hover */
}


/* footer */
.footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

.footer p {
    position: absolute;
    width: 100%;
    left: 0;
    bottom: 0;
    box-sizing: border-box
    min-height: 80px;
    padding-top: 5px;
    text-aling: center;
    color: green;
    background-color: #4CAF50;
}


# Mind Challenge

Project Description
Mind Challenge is an interactive web application designed to test your knowledge on various topics through a quiz. The goal is to provide a fun and educational experience for users, allowing them to assess and expand their knowledge on a variety of subjects.

## Features

### Existing Features
-__Header__

- The header, located at the top of the page, displays the game name "Mind Challenge" in a clear font that contrasts with the background.
-This header clearly informs the user about the game they are playing.

-__Quiz Options__

- The quiz options section includes clear instructions and a field for the user to enter their username.
- Interactive buttons allow the user to start the quiz and navigate through the questions.

-__Quiz Questions__

- Quiz questions are displayed one at a time with multiple choice answers.
- Each question is accompanied by interactive answer buttons.

-__Quiz Results__

- At the end of the quiz, the user's score is displayed along with an option to restart the quiz.

-__Responsiveness__ 

- The design is responsive, ensuring the application works well on devices of different screen sizes, including desktops, tablets, and smartphones.

### Features Left to Implement

- Future plans include expanding the game to include more questions and potentially new functionalities.

## Screenshots

Home page with a username field and a button to start the quiz.


Example of a quiz question with multiple choice answers.


Display of the user's final score and an option to restart the quiz.

## Testing

- Tested on different browsers: Chrome, Firefox, Safari.
- Confirmed that quiz results are always correct.
- Verified that the header, instructions, options, results, and footer text are all readable and easy to understand.
- Confirmed that the chosen colors and fonts are easy to read and accessible by running it through Lighthouse in DevTools.

## Bug Fixes

### Solved Bugs

-__Issue Deploying the Project on GitHub Pages__

- Identified that absolute paths were causing issues when deploying the project.
- The solution was to remove the leading slash from the paths in the code, as shown below:
<link rel="stylesheet" href="assets/css/styles.css">

### Unresolved Bugs

- No unresolved bugs at this time.

## Deployment

- The site was deployed to GitHub Pages. The steps to deploy are as follows:
   - In the GitHub repository, navigate to the Settings tab.
   - In the Source section of the dropdown menu, select Master Branch.
   - Once selected, GitHub will provide the link to the completed website.
- The live link to the site can be found here.

## Credits
### Content
 - The code to fix the footer to the bottom of the page was taken from w3Schools.
### Media
 - The images of cartoon hands were taken from ClipArtMax.

## Validation
### HTML
- No errors were found when passing through the official W3C validator.
### CSS
- No errors were found when passing through the official (Jigsaw) validator.