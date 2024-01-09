# Proactive For Her - Software Development Engineer I Frontend Challenge

## Introduction

Welcome to our coding challenge designed to assess your practical skills in building applications with Next.js and React. This challenge allows you to showcase your ability to create structured, maintainable, and efficient code. This activity is purposely limited in scope to be respectful of your time while still enabling you to demonstrate how you approach and solve problems. If invited to an hands-on interview, you'll pair with us to extend the service you created. We'd much rather see how you work on a problem you're familiar with than on some clever whiteboard puzzle we spring on you.

At this stage, we care most about:
- Interpreting written specifications (following instructions)
- Good design decisions
- Ability to consider edge cases
- Documentation

### Expected Technologies
You will be using Next.js and React to complete this challenge. You may use any additional libraries for state management, styling, or other purposes as you see fit.

Include a `README.md` file in your project with the following details:
1. Instructions for installing and running your project.
2. A summary of any build steps or dependencies.
3. A brief explanation of the decisions made during development.

### How to Begin
Fork this repository, create a new branch for your work, and push your progress to that branch. Please do not merge your branch into the main branch. . Do not merge the code into main. Oh, and don't squash your commits. We'd like to see the milestones of your progress. 
When you're done, push your code to this repo and email us.

Once you are finished, send us an email with the link to your repository branch.

&nbsp;
## The Challenge: Users & Posts Interaction

Develop a Next.js application that provides interfaces for displaying users and posts, with detailed views for each.

### Tasks
1. **List Users**: Create a page at `/users` that fetches and displays a list of users.
2. **User Details**: Implement dynamic routing to create a page at `/users/[id]` that displays details for a specific user and all posts associated with them.
3. **List Posts**: Create a page at `/posts` that fetches and displays a list of posts.
4. **Post Details**: Implement dynamic routing to create a page at `/posts/[id]` that displays details for a specific post and all comments associated with it.

#### Mock API Endpoints:
- **List Users**: `GET https://jsonplaceholder.typicode.com/users`
- **User Details**: `GET https://jsonplaceholder.typicode.com/users/[id]`
- **List Posts**: `GET https://jsonplaceholder.typicode.com/posts`
- **Post Details**: `GET https://jsonplaceholder.typicode.com/posts/[id]`
- **Comments**: `GET https://jsonplaceholder.typicode.com/comments?postId=[id]`


## Basic Wireframe Design

### Users Page (`/users`)
- A simple list view showing user names.
- Clicking on a user name navigates to the user details page.

### User Details Page (`/users/[id]`)
- Display the user's name, email, and address.
- Below the user's details, show a list of titles linked to their posts.

### Posts Page (`/posts`)
- A simple list view showing post titles.
- Clicking on a post title navigates to the post details page.

### Post Details Page (`/posts/[id]`)
- Display the post's title and body.
- Under the post's content, show a list of comments.