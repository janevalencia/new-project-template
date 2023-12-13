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

## Data / API Information

## Methodologies

### Tech Stack

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