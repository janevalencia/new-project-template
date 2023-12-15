# Project Proposal

Briefly (1-2 sentences) write down what your project is about. Example: "This project is about creating a web application that allows users to create and share their own recipes."

## Goal

What is the goal of your project? What do you want to achieve? Bullet points are fine.

Example: 

- A web application that allows users to create and share their own recipes. 
- Users can create an account, log in, create recipes, and share them with other users. 
- Users can also view recipes created by other users and save them to their own account.

## User Profile

Describe what kind of users will visit your app, including the demographics of your user.

Example:

There'll be two users type:
- Admin
  - Admin can create, update, and delete recipes.
  - Admin can create, update, and delete users.
- Regular users
  - Regular users can create, update, and delete their own recipes.
  - Regular users can view recipes created by other users.
  - Regular users can save recipes created by other users to their own account.

## Data / API Information

What data do you plan on using in your application? Where will you get this data? What data will you store in your database? What external API will you use?

## Methodologies

### Tech Stack

List down the technologies that you will use in your project. Example:

- Python
- Flask
- SQLAlchemy
- and so on

### Database Schema

- Attach your ERD (Entity Relationship Diagram) here. Example:

![ERD](/path/to/image.png)

- Write down any assumptions you make for others to understand your reasons behind the architecture design. Example:

  - A user can create many recipes.
  - A recipe can have many ingredients.
  - A recipe can have many steps.
  - A recipe can have many comments.
  - A user can have many comments.
  - A user can have many saved recipes.
  - A recipe can have many saved users.

### Security

- How will you handle security in your project? Example:

  - User passwords will be hashed using bcrypt.
  - User sessions will expire after 30 minutes of inactivity.
  - User passwords will be validated using the `password-validator` library.

- Is there any sensitive information that you need to protect in your app? Example:

  - User passwords
  - User email addresses

## Features

List the features of your project. 

- Use MoSCoW analysis here, make a table.
- Include all features that you want to implement in your project.
- Describe the feature that is more than CRUD. Example: "Users can share new recipe with other users in social media (Facebook, Twitter)."

Reference to MoSCow: https://www.productplan.com/glossary/moscow-prioritization/ 

Example:

MUST-HAVE

| Feature | Estimated Time | Actual Time |
| ------- | -------------- | ----------- |
| A       | X hrs          | X hrs       |

SHOULD-HAVE
| Feature | Estimated Time | Actual Time |
| ------- | -------------- | ----------- |
| A       | X hrs          | X hrs       |

COULD-HAVE
| Feature | Estimated Time | Actual Time |
| ------- | -------------- | ----------- |
| A       | X hrs          | X hrs       |

### Tasks

Reference to the project board and issues here. Example:

- [Project Board]()
- [List of Issues]()

**Upon creating a new issue, remember to set the following:**

1. Task title & Task Code (e.g. `T1: Create a new recipe`)
2. Task description: Describe the requirement of your task and what you need to do to complete the task (bullet points). Refer to this example issue: https://github.com/users/janevalencia/projects/7/views/1?pane=issue&itemId=47415190 
3. Add feature label your task appropriately (e.g. 'frontend' for frontend / UI related tasks, 'backend' for backend related tasks, 'bug' for bug fixes, and so on)
4. Add story points label to your task (e.g 'SP_1' for 1 story point, 'SP_2' for 2 story points, and so on)
5. Assign the task to yourself


**Upon setting story points, use this guideline as reference:**

| Story Points | Description                                                                                                                                                                                                              |
|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1            | Very simple / trivial task, you can do it in (max) 1 hour                                                                                                                                                                |
| 2            | Simple / decent / not too difficult task, you can do it (max) a day                                                                                                                                                      |
| 3            | Difficult task, you’re not immediately sure of how to solve it, needs some further research, but you know the underlying concept on how to solve it.                                                                     |
| 5            | Difficult complex task, requires extensive research, a lot of features combined into one ticket. This will not be a story / task, this will be something more of an Epic ticket.  **Needs to be broken into smaller tasks.** |

## User Flow Diagram

Attach your user flow diagram here. 

![User Flow Diagram](/path/to/image.png)

It doesn't have to be a full mockup. It could be a simple diagram / drawing using draw.io or LucidChart.

Reference: https://www.lucidchart.com/blog/how-to-make-a-user-flow-diagram 

## Challenges & Risk Mitigation

Describe what type of issues you might run into with your API or during the development of your project. Example:

| Challenges     | Risk Mitigation Plan / Strategy |
| -------------- | ------------------------------- |
| API down       | Alert users that this feature is unavailable due to xxxx |

## Out of Scope

Discuss what is out of scope for your project. Example:

- What is your project limitation?
- What are the features that you will not implement in this project?
- Anything that are not explicitly mentioned in the original scope
- etc 