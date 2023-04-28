---
layout: essay
type: essay
title: "The Building Blocks of an Application"
# All dates must be YYYY-MM-DD format!
date: 2023-04-27
published: true
labels:
  - Software Engineering
  - Design Patterns
---

<img width="300px" class="rounded float-start pe-4" src="../img/design-patterns.jpg">

## The Value of Design Patterns
When building any application without proper organization, a developer’s code is at risk of becoming unruly and unmanageable very quickly.  Design patterns offer a way to mitigate this issue by allowing a coder to split up their code into smaller, more manageable pieces. When playing with legos, by putting together certain blocks you can make a house, but if you rearrange these same pieces and maybe add in a few new ones for extra flair, your house can easily be changed into a boat.  Much like these legos, design patterns can be mix-and-matched to create different functionalities in one’s app.

## Fun With Legos
Just like how there are different types of legos, there are different types of design patterns.  Depending on the developer’s goal, different types of design patterns are more suited for different tasks.  Module Patterns that are used to split up code into smaller, reusable pieces are more suited for properly cutting down and organizing one’s code.  Compound Patterns where you create multiple components that work together to perform a single task, however, are best suited for creating very specific parts of an application (ex. a button that allows a user to edit or delete an item).  

The full extent of the usefulness of design patterns is best shown in the making of large-scale applications as demonstrated in my ICS 314 Software Engineering group project my group members and I have affectionately titled “Manoa Recipes.”  Throughout the development of our application, my group has kept our code in separate files and divided these files into folders based on their functions.  For example, the Navbar.js file which renders the Navigation Bar at the top of every page in Manoa Recipes can be found in the components folder while the VendorProfile.jsx file which renders the main body of a vendor’s profile page can be found in the pages folder.  This makes these specific pieces of code easier to find as well as gives me and my team members the ability to easily reuse these pieces later when building different pages of our website.
