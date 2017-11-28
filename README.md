# Capstone Project Plan

## Overview

I would like to create a Budget Tracker application, which would allow the user to set budget categories and amounts, and then track monthly spending against this goal.  There would be a mobile screen which would allow the user to enter purchases at stores as they are made.  Users could mark items for follow up and/or as tax-related/deductible.  Reports would show spending against goals (perhaps in a bar graph type display).

## Features

* User login, with the ability to add multiple users to a budget
* Create/read/update/delete budget categories and target amounts
* Functionality to add expenses to apply to a budget category
* Reports/progress bars to show spending which has occurred against monthly or year-to-date budget categories
* Ability for users to manage multiple budgets - if a user manages more than one budget, their initial screen should allow them to select which budget they would like to work with

## Possible Features To Add Later:

* Ability to capture photos with mobile app to save receipts if needed
* Queries for expenses by payment type (credit card "A", debit card, etc.) which allow user to enter date range.  This could be used to check against statements so users could identify potentially fraudulent charges.
* Ability to enter a transaction as a split.  The user should be able to optionally enter a sales tax rate and the total split amount should calculate automatically.
* If users manage multiple budgets, perhaps they can select a default budget to work with and there would be a way to switch to another budget if they would like (menu item or drop-down selection perhaps)
* Reports to show items marked for follow-up or identified as tax-related

## Technologies

* Java back-end to store budget information and expenses in database
* HTML/CSS/JavaScript front-end to establish budget categories and add expenses
* Mobile app written in Swift to add expenses and capture photos of receipts
* Database - possibly MySQL

## What I'll Have to Learn

* JavaScript
* Front-End Frameworks
* How to Deploy an Application
* Authentication