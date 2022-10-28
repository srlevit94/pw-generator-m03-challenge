# Random Password Generator

## User Story
- AS AN employee with access to sensitive data
- I WANT to randomly generate a password that meets certain criteria
- SO THAT I can create a strong password that provides greater security

## Acceptance Criteria
- GIVEN I need a new, secure password
- WHEN I click the button to generate a password
- THEN I am presented with a series of prompts for password criteria
- WHEN prompted for password criteria
- THEN I select which criteriaa to include in the password
- WHEN prompted for the length of the password
- THEN I choose a length of at least 8 characters and no more than 128 characters
- WHEN asked for character types to include in the password
- THEN I confirm whether or not to include lowercase, uppercase, numeric, and/or special characters
- WHEN I answer each prompt
- THEN my input should be validated and at least one character type should be selected
- WHEN all prompts are answered
- THEN a password is generated that matches the selected criteria
- WHEN the password is generated
- THEN the password is either displayed in an alert or written to the page

## Major Features and Modifications
- After clicking "Generate Password" button, the user is asked to determine length and types of characters to include in password
- Application checks if length is a valid number 8-128. returns "undefined" and asks user to try again if value is invalid
- Based on answers to prompts, the application adds desired characters randomly into the text window.

## Relevant Links:
- Deployed Application: https://srlevit94.github.io/pw-generator-m03-challenge/
- GitHub Repository: https://github.com/srlevit94/pw-generator-m03-challenge

### Explanation about missing commit history
- there was an issue with the original repository I was working on
- BCS assistant advised me to make a new repo and copy files into it
- more commit history is in old repo. for reference: https://github.com/srlevit94/password-generator-challenge.m03

![web image 1](https://github.com/srlevit94/pw-generator-m03-challenge/blob/main/password.deployed.png?raw=true)
![web image 2](https://github.com/srlevit94/pw-generator-m03-challenge/blob/main/password.undefined.png?raw=true)
