# Homework Submission

In this assignment, I programmed four asynchronous REST commands and worked with a REST Server. My responses can be seen inside of index.js, and I describe them below.

## Task 1: List Branches

For this task, I found a GET branches API and spliced the owner name and repo name into the API call.

In the test class, I set the user and repo to check this repo.

## Task 2: Create a New Repo

For this task, I used the /user/repos POST API. This API creates a new repo under whichever user is currently authenticated. Here, I used options.json to specify the repo's name (which is passed into this function as a parameter).

In the test class, I set the repo name to be created as test-HW3-repo. (Note: This test returns a 422 if the repo already exists.)

## Task 3: Create a New Issue

For this task, I used an issues POST API. Similarly to earlier, I spliced in the user and repo parameters to the API call, and I used options.json to pass other, necessary information for creating the issue.

In the test class, I set a basic placeholder issue to be created within the test-HW3-repo. (Note: This is the new repo that was just created in the last test.)

## Task 4: Edit Repo (Enable Wiki)

For this task, I spliced in the user and repo names to the API call, then used options.json to force has-wiki to True. 

In the test class, I targeted this call to be to test-HW3-repo. 

## REST Server

This section did not include coding. Please see the screencast video included inside of this repo. 