# Task 5: Adding Tasks

## Description

For this task, we'll be creating a class to manage the tasks, adding a method to the class to keep track of tasks in our application, and connecting up the **New Task** form to create tasks.

## Walkthrough

### Step 1: The Setup

In this step, we'll re-organise our folder structure in preparation for the next few steps.

1. Create a `js` folder in your project if one does not already exist
2. Copy the existing js file into your `js` folder, and rename it to `index.js`
3. Update the `<script>` tag in your `html` file to use the new location of the `js/index.js` file.
4.  Create a `taskManager.js` file in the `js` folder
5. Add a `<script>` tag pointing to the `js/taskManager.js` file _before_ the `<script>` tag pointing to the `js/index.js` file.

### Step 2: The TaskManager Class

In this step, we'll create a `TaskManager` class that
will be responsible for managing the tasks in the application.

> #### Useful Resources for this step
> - [ECMAScript 2015 Classes](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Inheritance#ECMAScript_2015_Classes)

1. Create a `TaskManager` class in `js/taskManager.js`
2. Within the `constructor` of the `TaskManager` class, initialize a `this.tasks` property on the class equal to an empty array.

> #### Test Your Code!
> Now is a good chance to test your code, head over to `js/index.js` and do the following
>
> 1. Initialize a new instance of `TaskManager`
> 2. `console.log()` the `tasks` property
>
> **Expected Result**
> You should see an empty array logged to the browser.

## Example

Stuck? Check out the provided example in the [example/](example/) folder!

## Assessment

This will be assessed as part of [Sprint 2](https://docs.google.com/spreadsheets/d/1WPyC5aAZANBREZ_Z23YLATMUkkP_v65IEY2rdOCLAQ0/edit?usp=sharing) 
