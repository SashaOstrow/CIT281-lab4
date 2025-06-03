# Lab 4
Lab goals and outcomes:

    Part 1: Create initial Express Node.js web server
    Part 2: Initialize as a Node.js project folder using Node Package Manager (npm)
    Part 3: Add Express to project using npm, and test using Visual Studio Code (VSCode)
    Part 4: Add git repo, exclude node_modules folder from git, make commits
    Part 5: Fix MIME error, test, and commit
    Part 6: Add a second route with query parameters, test, and commit

Your updated code must:

    Display Hello, Guest if either first or last are not provided as query parameters
    Display Hello, First Last where the First and Last are whatever was provided as part of the query string
    Use JavaScript object deconstruction to extract the first and last property values in variables called first and last from the req.query object
    Use a ternary (? :) conditional operator to initialize a constant variable name to either "Guest" or use the query string values
    Use a template string literal within the send() method to return the name variable

This lab introduced the process of building a basic web server using **Node.js** and **Express**, while also practicing **npm package management**, **HTTP route handling**, **MIME types**, **query parameters**, and **version control with Git**.

