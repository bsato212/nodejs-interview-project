# nodejs-interview-project

Welcome! This challenge will help us gauge your knowledge and evaluate your full stack development skills. In this repo, you will find the instructions for developing a Node.js web application.

## Core Goals

The core goal is to create a simple but functional web application that has data, logic and view components. This application will consult the [Cat API](https://thecatapi.com/) and display detailed information about cat several breeds.

The landing page should display cards with the name and image of 5 breeds picked randomly. Clicking any breed should lead to a detail page where all information about the breed should be displayed. It should also implement a search box in the landing page allowing queries by breed name.

- Node.js 18
- Responsive layout
- Landing page with 5 cards
- Detail pages 
- Search by breed
  - Search results page should display results in cards
  - Clicking a search result should lead to its detail page

The core goals should be completed in full.

## Constraints

- Project must use the [Express framework](https://expressjs.com)
- Do not use Express's scaffolding tool
- Fetch API for HTTP requests
- i18n and a11y are not required
- Feel free to use other libraries (frontend or backend) as long as the constraints above are honored

## Deliverables

- Public GIT repository with source code
- README file in repository detailing implementation
- Live application URL

## Stretch Goals

- Add a widget to the landing page that allows users to browse breeds by alphabetical order
  - Once a letter is picked it should lead to a listing page similar to search results page
- Use Redis for caching
- [Jade/Pug](https://pugjs.org) templates
- CI/CD pipeline
