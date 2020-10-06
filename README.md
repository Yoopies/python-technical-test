# Worklife Python Technical test

This project serves as a technical test for middle-senior backend developers in Python.

## Overview

You are building an employee vacation handling system to manage leave.

All employees belong to a team. There can be many teams.

Employee vacations can be of two types:
* Unpaid leave
* Paid leave

Paid leave can then be of two types:
* RTT (overtime compensation in France)
* Normal paid leave (by default)

A vacation has:
* A type of vacation (as explained above)
* A start date
* An end date

#### Notes

For this project:
* There is no half-day leaves, only complete days.
* There is no employee balance.


## The project

You need to create an API to help manage vacations including:
* Models and relationships for the various entities
* Features logic (see below)
* Endpoints to interact with features

Your API should be able to handle **at least** the following features:
* Create employees
* Create, update and delete vacations
* Search for employees on vacation given various parameters
* When a vacation overlaps (or is contiguous to) another one, merge them into one.
Only works with vacations of the same type, else it will fail.


#### Bonus features
If you have the time/will, you can implement one or two more features:
* Searching should also return the number of vacation days for each employee (given the search parameters).
* Compare two employees and return the days they will be both on vacation


## What we expect

It should not take more than 4 hours to finish.

Your answer to this test should be a repository. Please refrain from forking this repository.

Feel free to implement this project in whatever way you feel like, we do not impose any limitations/requirements.
You can choose any framework (or no framework), any design pattern (or none), any database (or none) for this.
