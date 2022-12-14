# CS341W-FA22-Final
This final is open book and open web. You can use any resources and examples available to you; however, you cannot receive live assistance.

## Git Started
1. Clone this assignment repository to your own machine
2. Create a .gitignore file that ensures your node_modules folder is exempted

## Create a NodeJS Project
_NOTE: You can create a React application or an Express with Handlebars application._
1. Initialize a NodeJS project and install any other packages you might need.
2. Start with a basic "Hello, World" application that you can navigate to in the browser on port 3000.

## Set Up Pages/Views with Routes
1. In addition to your home page, set up a secondary page (or view) to be used for a list of books. 
2. Implement routing to ensure that users can navigate. _The path ("/") routes to home, while ("/books") routes to the list of books._  
3. Provide navigational links that allow the user to go between these two pages/views. 

## Display the Books Data
_NOTE: This codebase already has a BookData.json file._ 
1. Import the provided book data into your books page/view. You can either import the file directly or create a specific named export/import. (_You may not copy/paste the data into the view._)
2. Use templating (if using Express-Handlebars) or components (if using React) to iterate over the books object. 
3. On the books page/view, render a simple presentation of the following elements (along with a label) for each book:
- Title
- Author
- 
