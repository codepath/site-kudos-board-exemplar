# Kudos Board

## Introduction

In this project, you will be building a Kudos board that allows users to create themed boards and leave praise and notes of encouragement to other users.

We will put together our learnings from the previous four units to create our very first full-stack project from start to finish. You will work in your Capstone Pods for this project.

## Sample Site

For inspiration, you can view a simple sample website [here]([https://kudos-board.onrender.com/).

## Learning Goals

-   **Full-Stack Development Proficiency**: Develop expertise in full-stack development by mastering React for frontend interfaces and Node.js with Express for backend API creation, focusing on CRUD operations and database management.
-   **Deployment and Scalability**: Understand deployment strategies and techniques for hosting applications on platforms like Render, ensuring reliable application availability, scalability, and effective management of deployment processes.
-  **Effective Collaboration and Project Management**: Learn to collaborate efficiently within a team using version control systems like Git, while also practicing project organization, clear communication, and agile development methodologies.

## Project Requirements


Frontend:

-   React

Backend:

-   Node/Express
-   Postgres
-   Prisma
  
**Home Page**

-   Displays header, banner, search, board grid, and footer
-   Displays preview of all boards on initial page load
    -   Boards previews should show an image/gif and board title
-   Users can click on a category (recent, celebration, thank you, inspiration) to filter the boards
    -   Recent displays most recently created boards
    -   Other categories display boards of that type
-   Users can search for a board by name
-   Users can click on a board to navigate to a new page containing that board
-   Users can create a new board
    -   Board should have title, category, and author (optional)
-   User can delete boards
  
**Board Page**

-   Displays a list of all cards for a board
    -   Each card has text, gif found using the [GIPHY API](https://www.notion.so/Project-Kudos-Board-3d98a17f7e2d47c69f04f9ee3d2756b6?pvs=21), and author (optional)
-   Cards can be upvoted
-   Cards can be deleted
  
**Stretch (different branch)**

-   Add User authentication (w/JWT)
    -   Users can log in
    -   Boards and cards can be associated with a user
    -   New filter option on home page to show only user’s boards
    -   Only author of a card/board can delete
