Name: Kairatuly Miras

Group: IT 2504

Task 0. Navigation Bar
I used Flexbox to create the navigation bar. The justify-content: space-between property puts the logo and links on opposite sides, and align-items: center centers them vertically. I also used gap: 20px to make space between the links.

<img width="1895" height="144" alt="image" src="https://github.com/user-attachments/assets/6d13122c-27df-4821-884e-d5633c630629" />

Task 1. Card Row
Flexbox is used to put product cards in one straight row. Thanks to align-items: stretch and flex: 1, all cards have the exact same width and height. I also added a hover effect using transform: translateY(-5px) and a box shadow.

<img width="1834" height="932" alt="image" src="https://github.com/user-attachments/assets/0874d973-e523-41b9-b014-4145d81345a2" />


Task 2. Page Layout with Grid Areas
In this task, the basic page structure is built with CSS Grid. I used the grid-template-areas property to organize the blocks clearly: the header takes the full width at the top, the sidebar is on the left, the main content (main) is on the right, and the footer (footer) is at the bottom.

<img width="1871" height="544" alt="image" src="https://github.com/user-attachments/assets/e2fc1db4-7718-419f-b221-7c9b00f1a455" />

Task 3. Image Gallery
To create the gallery, I used CSS Grid with grid-template-columns: repeat(3, 1fr). This automatically divides the space into 3 equal columns. The row height is fixed (280px). For the gallery cards, I set up a hidden description (.overlay). It smoothly slides up from the bottom when you hover the mouse over the image.

<img width="1847" height="879" alt="image" src="https://github.com/user-attachments/assets/924ff2ce-84c8-459c-b9c8-9683ce5427e3" />

Task 4. Portfolio Page
In the final task, I combined both methods. Grid is responsible for the main section layout . Flexbox is used for specific parts: to align elements inside the header and for the structure inside the project cards, so the text and button are placed neatly.

<img width="1875" height="656" alt="image" src="https://github.com/user-attachments/assets/09cb2734-172d-4484-b0dc-4d389b4405c9" />

Summary of work process
During this assignment, I practiced modern methods for creating responsive layouts without using old techniques (like floats).

The work was divided into stages:

Learning and using Flexbox for one-dimensional layouts (aligning the navigation and creating a row of cards with equal heights and interactive effects).

Building two-dimensional layouts using CSS Grid (using grid-template-areas for the page structure and setting up a grid for the image gallery).

Combining both methods on the final portfolio page. Grid provides the global page structure, and Flexbox solves local alignment tasks inside specific components (cards and header).
