# FLUFFY CALCULATOR

_This Web page is about a simple **Calculator app**_.<br/>
_version: 8/04/2018_<br/>
_version updated: 18/04/2019_<br/>

_By **Josh Hortt**_

## Description

_This app is a demonstration of creating and using basic functions to create an evolving calculator_.<br/>
_That's why I called it **Fluffy Calculator**_.<br/>
_It explains the separation of the user-interface logic("front-end") and the business logic("back-end")_.<br/>

_The business logic and user interface logic are distinctly separate sections of the (scripts.js file)_.<br/>
_The user interface sections is responsible for gathering user-given values, parsing them into integers_,<br/>
_and calling our add() function when the user submits a form. It also displays the result of the add()_<br/>
_function directly on the page. Essentially, it's handling all interactivity with the user_.<br/>
_It can call a back-end function (as seen in var result = _add(number1, number2);), but the function_<br/>
_is not defined here in this block of code. That's the responsibility of the business, or back-end-logic_.<br/>

_The business logic contains functions for all capabilities that this calculator will eventually have_.<br/>
_It instructs the application what to do when a user opts to add two numbers, or when a user wants to_<br/>
_divide two numbers (a feature I will add later on). All logic here occurs behind the scenes_.<br/>
_The user interface logic may call one of the business logic's functions when necessary, but the these_<br/>
_functions themselves are defined in the back-end_.

## Update

_Now after exploring more JavaScript branching, I 'll add' all four capabilities to this calculator_:<br/>
_**Addition, subtraction, multiplication, and division** into a single form with a **single submit button** and **event listener**_.<br/>
_I'll add **radio buttons** that allow the user to choose whether they'd like to add, subtract, multiply, or divide_<br/>
_the two numbers provided in the form_.<br/>
_version updated: 24/04/2019_


## Setup/Installation Requirements

_Contribute to fluffy-calculator by cloning this repository_.

## Contribute

_**Issue Tracking**: github.com/Joshhortt/fluffy-calculator/issues_<br/>
_**Source**: github.com/Joshhortt/fluffy-calculator_

## Support and Contact Details

_If you have any issues or have questions, ideas, concerns, please contact: joshhortt@yahoo.com_

## Technologies Used

_**HTML_5** - Hyper Text Markup Language_<br/>
_**CSS_3** - Cascading Style Sheets_<br/>
_**BOOTSTRAP_4** - Bootstrap_<br/>
_**JQUERY_3.3.1** - JQuery_<br/>
_**VANILLA_JAVASCRIPT** - Javascript_

## License

_**MIT License. Copyright (c) 2018 Josh Hortt**_
