Question 1. Please explain what the following lines of code do

global.browser = new BrowserHelpers()
global.expect = chai.expect;


Question 2. Please explain why we are placing the let fizzBuzz = new FizzBuzz outside the it block?


Question 3. Please explain the difference between using === and == in JS?


Question 4. Why we are moving (number % 5 === 0) to the top?


Question 5. Please explain the difference between feature and unit test

--> With unit tests we are testing the logic behind the application to see it behaves as it supposed to do. Each function should be isolated and tested individually to return results fast.
--> With feature tests we are interacting eith the application in the same way as a real user would do. These tests take longer time than unit tests.


Question 6. Please explain what this following code does

describe('User can input a value and get FizzBuzz results', () => {
    before(async () => {
        await  browser.init()
        await  browser.visitPage('http://localhost:8080/')
    });

    beforeEach(async () => {
        await  browser.page.reload();
    })

    after(async ()=> {
        await  browser.close();
    })
})

Question 7. Please explain what expectations in the context of testing are


Question 8. Please write a line to line explanation of what is happening in this code

<script src="js/fizzbuzz.js"></script><script>
        document.addEventListener('DOMContentLoaded', () => {
            let button = document.getElementById('button')
            let displayDiv = document.getElementById('display_answer')
            button.addEventListener('click', () =>{
                let value = document.getElementById('value').value
                let fizzBuzz = new FizzBuzz
                let result = fizzBuzz.check(value)
                displayDiv.innerHTML = result;
            })
        })
</script>

Question 9. Please explain what a CDN (Content Delivery Network) is? 
--> CDNs allows quick distribution of internet content.