# [Part 1 - Introduction to React](https://fullstackopen.com/en/part1)

In this part, we will familiarize ourselves with the React-library, which we will be using to write the code that runs in the browser. We will also look at some features of JavaScript that are important for understanding React.

## Exercise 1.1 - 1.2 [courseinfo](./courseinfo/)

### 1.1 Course Information

Refactor the code so that it consists of three new components: Header, Content, and Total.

All data still resides in the App component, which passes the necessary data to each component using props. Header takes care of rendering the name of the course, Content renders the parts and their number of exercises and Total renders the total number of exercises.

### 1.2 Course Information

Refactor the Content component so that it does not render any names of parts or their number of exercises by itself. Instead, it only renders three Part components of which each renders the name and number of exercises of one part.
