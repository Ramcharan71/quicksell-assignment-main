![Screenshot 2024-09-13 141042](https://github.com/user-attachments/assets/3a75fed1-4781-415b-9024-fae4c37c23d2)
![Screenshot 2024-09-13 141125](https://github.com/user-attachments/assets/9d206c0e-d69a-4346-a538-46fa9425572b)

# *Use React JS for the Assignment*

*Design:* 

*Display state:* 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e1a13657-9dc2-496d-a5c7-b27be15e9fe0/Untitled.png)

*State based on display. - Grouping by user is selected.*

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/de6f9ade-433a-4185-a6df-4d396ea8be2d/Untitled.png)

*Grouping by priority is selected.*

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2f8e52ba-2b96-40e8-be6a-34e25dd240eb/Untitled.png)

*Card:*

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/896834d4-fe3d-4db5-bd76-29049439b0cb/Untitled.png)

*Api* :  https://api.quicksell.co/v1/internal/frontend-assignment 

You are required to create an interactive Kanban board application using React JS that interacts with the provided API from  https://api.quicksell.co/v1/internal/frontend-assignment

When a user clicks the "display" button and selects a grouping option, the Kanban board should dynamically adjust to reflect the user's choice.

The application should offer three distinct ways to group the data:

1. *By Status*: Group tickets based on their current status.
2. *By User*: Arrange tickets according to the assigned user.
3. *By Priority*: Group tickets based on their priority level.

Users should also be able to sort the displayed tickets in two ways:

1. *Priority*: Arrange tickets in descending order of priority.
2. *Title*: Sort tickets in ascending order based on their title.

The Kanban board should be responsive and visually appealing, with a design similar to the provided screenshots. 

*The priority levels for the tickets are as follows:*

- Urgent (Priority level 4)
- High (Priority level 3)
- Medium (Priority level 2)
- Low (Priority level 1)
- No priority (Priority level 0)

*Priority levels: (This values you will receive in the api)*

4 - Urgent

3 - High

2 - Medium

1 - Low

0 - No priority

Additionally, the application should save the user's view state even after page reload.

*Assets*

[Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/867c6222-5e73-49fb-b21f-a276ba2d258b/76bcb3fe-d025-4ad4-9247-e38c2935b859/Untitled.zip)

1. Don’t use css library like Bootstrap, Tailwind, Vite, Material UI, Charka…etc
2. Don’t use NextJs or similar framework. Code in pure ReactJS
3. Write Pure CSS Code only. No library for css (bootstrap,..etc). Styled JSX can be used though
