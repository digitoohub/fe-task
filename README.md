# Frontend Developer Task

## Introduction

- your task is to implement a simple single-user blogging engine frontend in React
- you don't have to complete all subtasks, just do what you have the time and skills for
- the goal here is not just to see if you can do an app, but how you do it. So please write it as if it were a big production app, that includes code structure, validations, usage of git, documentation, tests, etc.
- we realize that some subtasks can be very time consuming, if you just don't have the time, you can write short text description of how would you solve the problem
- on the flip side, you can improve on many things, if you have the time. For example, we don't need you to implement user registration, but you are free to do so
- feel free to use this exercise (including the instruction) for evaluation by other companies

## Technologies

- TypeScript is preferred
- Jest is preferred for unit tests, TestCafe or Cypress for e2e tests
- Sass for styling
- don't worry too much about styling, you can use bootstrap, material or some other library
- Webpack for bundling
- React Router for routing
- Redux, hooks or Apollo Link for state management
- Axios for HTTP requests

## The task


- check out the API [here](api.yml)
- check out the WS API [here](ws.json)
- implement the [wireframes](https://www.figma.com/file/y5ys3jnMFl4Zcse9BZt0GZ/Digitoo-fe-task?node-id=2%3A2)

### User Perspective

- Article List

  - display a list of all articles, ordered by date descending
  - each article should show title, perex and publication date
  - each article should have a link to the full text

- Article View

  - display an article
  - article should be in markdown, take care of proper rendering

- New Article View

  - display a page with form to add new article
  - the form should take title, perex and content
  - the content should be in markdown, you can use some existing markdown editor
  - add necessary validations
  - this page should be protected by password

- Add Comment functionality
- display comments on Article View page
- each comment should have content, timestamp and author
- add comment form to Article View page
- comment form should take author and content

- Add Comment voting functionality
  - add the ability to vote on comments (+/-)
  - display score on each comment

### Admin Perspective

- Login Screen

  - implement login
  - after successful login redirect to next screen
  - on unsuccesful login display error message

- My Article List

  - display table of all articles
  - display a button to create new article
  - implement edit and delete buttons
  - optionally implement article ordering

- Article Detail View

  - display editable sections of article
  - implement publish button
  - use some existing Markdown editor, unless you really want to implement your own
