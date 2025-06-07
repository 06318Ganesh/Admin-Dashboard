# Admin-Dashboard



An Admin Panel typically has several sections that enable the administrator to manage and control various activities on a website. The layout usually consists of a header and a sidebarnavigation bar, which allows the admin to easily navigate between the various sections of the panel. In the header, there will also be a search button, enabling the admin to directly search for a module.



Approach to Create a Responsive Admin Dashboard
1. Set Up the Project Structure: Begin by creating a folder for your project. Inside the folder, create three files:

index.html: The file for the HTML structure.
style.css: The file for styling the dashboard.
index.js: The file for adding interactivity using JavaScript.
2. Create the Header Section: The header typically contains the logo and essential options like the menu button, admin profile picture, and a search bar.

Use the <input> tag to create a search bar and apply styling using CSS.
Use Flexbox for the header to align and space the items properly
3. Design the Sidebar (Navigation Bar):

Position the sidebar on the left side of the screen using relative positioning.
Implement a JavaScript function that will open and close the sidebar when the menu button is clicked. This can be done using the addEventListener() method.
4. Create the Main Content Area:

Create a <div> for the main body of the dashboard.
In the upper section of this div, add four cards that display essential information such as Daily Views, Likes, Comments, and so on.
Use Flexbox properties to align and justify these cards. Apply flex-wrap: wrap; to ensure that the cards remain responsive and adjust based on the page size.
5. Recent Articles Section:

Below the cards, create a square <div> to display recent article information.
Apply overflow-x: scroll; to make the horizontal overflow of this section scrollable.
Use Flexbox to align the content within this section to the right.
6. Make the Page Responsive:

To ensure the dashboard is responsive, add media queries at different breakpoints.
Adjust the styling according to the screen size.
