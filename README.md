# Pythonic-Garage-Band

Creating a Garage Band with Object Oriented Programming.

## Run Locally

We are deployed on [Link](https://github.com/kevinhenry/pythonic-garage-band)

PR: [Link](https://github.com/kevinhenry/pythonic-garage-band/pulls)

Web Application
In this lab assigment we were provided with a unit test file and some starter code. We had to then statisfy the feature tasks by creating classes and methods and assigning attributes.

## Feature Tasks and Requirements

Use Python classes to model a `Band` made up of different kinds of musicians.

Start with `Guitarist`,`Bassist`, and `Drummer`.

Make use of a `Musician` base class to handle common functionality which particular kinds of musicians will inherit.

### User Acceptance Tests

Unit tests will be supplied for this lab. Your job is to make them pass. Do NOT modify the supplied tests (except to enable for stretch goals.)

### Band Tests

A `Band` instance should have a `name` attribute which is a string.
A `Band` instance should have a `members` attribute which is a list of instances that inherit from `Musician` base (or super) class.
A `Band` instance should have a `play_solos` method that asks each member musician to play a solo, in the order they were added to band.
A `Band` instance should have appropriate `__str__` and `__repr__` methods.
A `Band` should have a class method `to_list` which returns a list of previously created `Band` instances

### Musician Subclass Tests

Each kind of `Musician` instance should have appropriate `__str__` and `__repr__` methods.
Each kind of `Musician` instance should have a `get_instrument` method that returns string.
Each kind of `Musician` instance should have a `play_solo` method that returns string.

### Stretch

See tests marked “stretch” in supplied test suite.
Make Musician “abstract” - aka an Abstract Base Class
Add your own tests.

## Tools Used

VS Code PyCharm

Python
Pytest
Poetry
PyEnv

## Getting Started

Clone this repository to your local machine.

$ git clone [Link](https://github.com/kevinhenry/pythonic-garage-band.git)
Once downloaded, activate your virtual environment and run by ____________

`poetry init`
`poetry shell`

Collaboration with Anthony Wiliams
And Stack Overflow

Please adhere to this project's `code of conduct`.

![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

## License

[MIT](https://choosealicense.com/licenses/mit/)
