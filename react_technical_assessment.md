# Technical Assessment

At [Kredi](https://www.kredi.mx), We are focused on critical financial processes. That is why we want our development team to focus on quality code and best practices.

This is a small technical assessment for our open position as Sr. Frontend Sofware Developer. We encourage you to follow the rules described above:

- Be honest, do not copy code from Stack overflow, We all know programmers do that, but this time we want to evaluate your thinking process.
- Do not mention the company name in your repository.
- Apply best practices, var names, indentation, readability, SOLID, DRY, Design patterns, etc.
- Test your code.
- Publish your code on Github || Gitlab, be careful about how you write your commit messages.
- Deploy your code to Heroku or Firebase, it takes no longer than 20 minutes!
- if you have any questions, do not hesitate to reach us, this is so important!
- Happy coding! :)

## Part I

### Questions

Please add a file called `excercises.md` to your repo with your answers:

#### CSS

1. How do we make a rounded corner by using CSS?

2. What is a CSS pseudo-class?

3. Differences between the ID and class.

#### JS (ES6)

1. What is ES or ECMAScript or ES6?

2. What is an arrow function? What are all its uses? How it differs from a normal function?

3. What is a generator function?

#### ReactJS

1. What is ReactDOM and what is the difference between ReactDOM and React?

2. What are the differences between a class component and functional component?

3. What is the difference between state and props?


## Part II
### CHALLENGE

Your mission is to make a small Pomodoro time tracking app.


> (if you do not know about the Pomodoro technique, please refer to [this link](https://francescocirillo.com/pages/pomodoro-technique))


+kudos If you use docker, that would be great and give extra points.

### CORE REQUIREMENTS

#### Pomodoro technique

```md
The core process of the Pomodoro Technique consists of 6 steps:

1. Choose a task you'd like to get done.

2. Set the Pomodoro for 25 minutes.

3. Work on the task until the Pomodoro rings.

4. When the Pomodoro rings, put a checkmark.

5. Take a short break (5 minutes)

6. Every 4 Pomodoros, take a longer break

```

Write an app with React JS that follow the user stories above:

- As a visitor, I want to create an account for the Pomodoro app, so that I become an active user.
    Acceptance Criteria:
      - Application needs my name, email, and password.
      - Duplicated emails are not allowed.
      - Validates email input.
- As an active user I want to see my home screen where I can see my Pomodoro timer.
    Acceptance Criteria:
      - My timer should have a large format (easy to see).

      - I will be able to start a Pomodoro timer.

      - I will be able to pause a Pomodoro.

      - After my Pomodoro ends, a 5 minutes timer starts, indicating it is a short break.

      - After four Pomodoros, a 30 minutes timer starts, indicating it is a long break.
    This is an example of how the app might look like, however, you can design it.
    ![Example](pomodoro-wireframe.svg)
- As an active user I want to be able to write what task am I working on.
- As an active user, If I want to close the window or tab, I want to see an alert preventing.
- As an active user I want to see all my completed pomodoros in a list.