#Web Technologies Project 2 
---

To-Do Web App
---


Name: "Salman Sohail" 
---

Roll No : "2652"
---

To-Do Web App
---

Table of Contents
Overview
---

Features

Project Structure

Step-by-Step Instructions & Solutions
---

Setup Instructions
---

Overview
Welcome to the To-Do Web App project! This repository contains the starter code and implementation instructions to fix and enhance a web application using CSS Flexbox. The application is designed to help organize priorities for the week with a clear, responsive layout.
---

Features
Visual Priorities: A distinct weekly grid for Monday through Friday.

Reminders Section: A dedicated section for important reminders.

Responsive Layout: Uses CSS Flexbox to ensure layout elements wrap and align correctly across various screen sizes.

Project Structure
Plaintext
├── index.html        # Main HTML structure
└── style.css         # Styling for the web app
Step-by-Step Instructions & Solutions
To complete the project, apply the following CSS properties to the corresponding rulesets in the style.css file:
---

Task 1: Flex Containers
Update elements with the classes .container, .square, .week, and .reminders to be flex or inline-flex containers:

CSS
.container {
  display: flex;
}

.square {
  display: flex;
}

.week {
  display: inline-flex;
}

.reminders {
  display: inline-flex;
}
---

Task 2: Flex Grow
Make the week container take up more space proportionally compared to reminders:

CSS
.week {
  flex-grow: 3;
}

.reminders {
  flex-grow: 2;
}
---

Task 3: Flex Direction
Set the direction of the .week elements to column:

CSS
.week {
  flex-direction: column;
}
---

Task 4: Flex Wrap
Allow row elements to move to the next line when the container is resized:

CSS
.row {
  flex-wrap: wrap;
}
---

Task 5: Justify Content
Add space around each item in .row and center items within .square:

CSS
.row {
  justify-content: space-around;
}

.square {
  justify-content: center;
}
---

Task 6: Align Items
Vertically center the items inside both the .row and .square containers:

CSS
.row {
  align-items: center;
}

.square {
  align-items: center;
}
Setup Instructions
Prerequisites: Use the Google Chrome browser to prevent compatibility issues.

Files: Make sure both index.html and style.css are located in the same directory.

Execution: Open index.html directly in your web browser. Resize the window to see the responsive flexbox properties in action.
---
Thank You Sir
