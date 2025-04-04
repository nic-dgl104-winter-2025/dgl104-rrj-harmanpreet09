[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MMj2nZMu)
# Rsearch and Reflection Journal
Research and Reflection Journal for DGL 104 course

# WEEK 8

This week felt like a big shift in the course. So far, we’ve mostly been learning the basics of good coding — like writing clear documentation, fixing bugs, testing, and reviewing code — through activities like the MIT App Inventor assignment and the Programming Practice Article. Now, we’re stepping into real development, where we’ll start building with a specific programming language and focus on things like design patterns, app structure, and writing actual user requirements.

I also got started with my Research and Reflection Journal! I accepted the GitHub Classroom invite and created my own journal repo where I’ll be tracking all my weekly progress and reflections from now until the end of the semester.

## Language Research: Lua
For our language research activity, I picked Lua — I had heard of it before but never really looked into it. 

It turns out Lua is a small and fast scripting language that’s used a lot in video games (like Roblox and World of Warcraft) and embedded systems.

Who uses it? Game developers, hardware engineers, and software teams working with embedded tech.

Why it’s useful: Lua is great for extending programs or customizing apps without making them heavy or slow.

Some helpful resources I found:

Lua.org – the official documentation, straight from the creators.

Learn Lua in Y Minutes – a nice quick overview for fast learners.

GitHub repositories – good to see how real people use Lua in actual projects.

Writing User Stories (Using Instagram)

For the user story activity, I picked Instagram since I use it almost daily and understand the features well.

## Here’s a general story:

As a user, I can post a photo to share with my followers.
More detailed ones:

As a user, I can add filters before sharing.

As a user, I can tag friends in the photo.

As a user, I can write captions and add hashtags.

As a user, I can schedule my post for later.

Acceptance criteria for tagging friends:

There’s a “Tag People” option before posting.

I can search usernames and tag them easily.

Tagged users show up as clickable names on the post.

The tagged person gets a notification.

Doing this helped me think like a developer. It’s not just about what the feature is, but also how it should behave and how the user will interact with it.


# Week 9 

This week was all about learning how to write better, smarter code — and also how to be part of something bigger by contributing to open source projects. We also continued working on our group project, which is starting to feel real now!

## What Are Design Patterns, and Why Do They Matter?

I spent time learning about design patterns, which are like reusable solutions for common coding problems. They’re not pieces of code you just copy and paste, but more like blueprints or ideas you can use in your own way. The cool part is that other developers understand these patterns too, so it makes teamwork and maintenance way easier.

## Here are four patterns I looked into:

1. Singleton Pattern
This one makes sure you only have one version of something — like a login session or a settings manager. I can see myself using this if I ever build an app where users need to stay logged in.

2. Observer Pattern
This one’s like the "notify me" option on YouTube. When something changes, like someone uploads a video, all the subscribers (observers) get notified. I could use this in apps where users follow updates or posts.

3. Factory Pattern
This pattern helps create objects without having to know exactly which one you need ahead of time. For example, if someone selects “dog” or “cat” in a pet adoption app, the factory pattern would generate the right kind of pet object.

4. MVC (Model-View-Controller)
This one helps separate your app into three parts: the data (model), the user interface (view), and the logic (controller). We’re planning to use this in our group project so it doesn’t turn into a messy pile of code later.

### Group Project Progress – Smart Task Management System (STMS)

The idea behind our project is to create a smart system where users can easily create, assign, and track tasks. But instead of just a basic to-do list, we’re planning to add features like:

AI that suggests task priorities

Different user roles like Admin, Team Lead, and Team Member

Notifications when tasks are updated

Task status tracking (To Do, In Progress, Done)
Visual dashboards and reports

And more advanced stuff like task dependencies and auto-assignment!

We're using PHP, MySQL, and JavaScript to build the system. So instead of using a heavy framework like Laravel or MVC architecture, we're keeping things a bit more lightweight and flexible. PHP will handle the backend logic, MySQL stores the task and user data, and JavaScript is used to make the site interactive and dynamic on the frontend.

 What We've Done So Far
Right now, we’re in Phase 1, and here’s what we’ve worked on:

We created our GitHub repository and shared it with the instructor
 
We planned out the key features we want to build and assigned tasks within the group

We started setting up the file structure using PHP for the backend and MySQL for the database

 We’re starting to build user registration and login functionality (with different roles)
 
After that, we’ll move into creating and assigning tasks, with deadlines and priority levels

We’re following good practices like using pull requests, writing clear commit messages, and documenting our process in a README and CONTRIBUTING file. Even though 

we’re not using MVC, we’re keeping our code modular by separating frontend (HTML/JS), backend (PHP), and database queries (SQL) into different files.

# Week 10

## Understanding the MVC Pattern
