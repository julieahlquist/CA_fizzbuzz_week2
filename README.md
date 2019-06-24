# FizzBuzz challenge - JavaScript
### Craft Academy - June 2019 - Week 2

--> [Check it out here](https://focused-easley-c2fd5b.netlify.com/) <--

## 1. Description
This is an individual weekend challenge of week 2 at Craft Academy, aiming to solve the FizzBuzz Challenge using JavaScripta and deploying it on a styled webpage. In addition several questions regarding the projects has been answered below.

## 2. Prerequisites
- Initialize npm
- Install Training Wheels [package](https://www.npmjs.com/package/e2e_training_wheels)

## 3. Testing
Both unit and feature tests has continously been carried out thoughout the project using npm spec/feature tests. 

## 4. Authors
* **Ahlquist, Julie** - [julieahlquist](https://github.com/julieahlquist)

## 5. Acknowledgments
Thank you to Craft Academy in Stockholm, Sweden for crafting this challenge.

Thanks to PurpleBooth for the README template https://gist.github.com/PurpleBooth/109311bb0361f32d87a2
___
Question 1.

--> The lines above are requiring BrowseHelpers from e2_training_wheels and chai from modules. Global means we initialize these on a global scope. BrowseHelpers let us run the code in the browser and chai is a library tool for BDD.
____
Question 2.

--> We wish to require fizzBuzz on all it blocks, so rather than typing it multiple times we do it outside.
____
Question 3.

--> === is testing for strict values, meaning they have to be exactly the same, while == is more 'accepting' as for instance the number 10 can be equal to '10' (10 == '10')
____
Question 4. 

--> I dont think it matters that much if % 5 or % 3 is at the top, but when we add the code for % 15 that has to be put at the top in order to be executed first.
____
Question 5. 

--> With unit tests we are testing the logic behind the application to see it behaves as it supposed to do. Each function should be isolated and tested individually to return results fast.
--> With feature tests we are interacting eith the application in the same way as a real user would do. These tests take longer time than unit tests.
____
Question 6. 

--> This piece of code opens the browser at the local host page, checks each input value and its results and then closes the browser.
___
Question 7. 

--> What we test is our expectations on how we want and suppose our code will behave.
___
Question 8. 

--> The first line of code calls the JS file, the second one second one sets an event listener which "simulates" how our application would behave if a user would interact with it. Then we get the value by its id and then display the result of that value by using our index.html file. 
___

Question 9. 

--> Content Delivery networks are geographically separated servers that allows quick distribution of internet content through html files.
___