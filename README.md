# QA Technical Task

A QA Technical interview based on an example with requirements and wireframes.

<hr>

## Table Of Contents

* [Description](#description)
* [Wireframes](#wireframes)
* [Assumptions](#assumptions)
* [Requirements](#requirements)
* [Installation](#installation)

<hr>

## <a id="description"></a>Description

Using the requirements and wireframes below, create a feature file to verify user input and UI options. 
Please, write using Gherkin language with Given/When/Then format. 

<hr>

Story1: 

In Order to apply for a health insurance
As A Online customer
I Want a facility to capture customer's Health Plan needs


Assumptions
1. Customer enters data in the online system, and each new field appears upon the completion of the previous. 


Requirement 1: Capture Who the health plan is for
1. Available options in drop down are:
  myself only
  myself and my partner
  myself and my children
  myself, my partner and my children
  a group of people
  
Requirement 2: Capture customer's age
1. Valid input is 19 to 100 years
2. Validation for characters and special symbols is done on input
3. If the input is incorrect, display error message "Only numbers from 19 to 100 are allowed"



<hr>

![alt text](wireframes/first-screen-qa-test.jpg "Title")

Second one: 

![alt text](wireframes/second-screen-qa-test.jpg "Title")
