
# Cypress GHActions 

Welcome to the Cypress GHActions repository! This repository is a simple example of how to set up Cypress end-to-end tests to run automatically using GitHub Actions.

## Requirements
Before you can use this repository, you must have the following installed on your system:
    Node.js
    Git

## Installation

Clone this repository onto your local machine using the following command:

```bash
  git clone https://github.com/eduardolopez-gm/cypress-ghactions.git
```

Install the dependencies by navigating into the cypress-ghactions directory and running:

```bash
  npm install
```

After that, you should have installed project dependencies and you will be ready for next step.

## Running Tests

To run the tests locally 
In interactive mode 
```bash
  npm run cy:open
```
In headless mode run 
```bash
  npm run cy:run 
```

To run the tests in the GitHub Actions workflow, simply push changes to this repository, and the workflow will automatically start.

## Authors

- [@eduardolopez-gm](https://github.com/eduardolopez-gm)

