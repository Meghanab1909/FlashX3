This project is in a reactjs framework. 
src folder - Primary files are App.js and App.css. In the src folder, there is a components folder that consists of js and css files, this facilitates linking of different 
             files/pages together. React Router DOM is used for linking. The required formatting files (like background, logo etc.,) are also present.
public folder - Primary files are the HTML files and other formatting files (like background, logo etc.,) are present.
(node modules folder is present but not uploaded on github. Only the src and public folder have been uploaded)

To run this project:
(Assuming Nodejs and MongoDB are installed)
1. Create a react app using the command: npx create-react-app flashx3 [OR] create-react-app flashx3
   The react app shall be downloaded.
   
2. Open the terminal with the path set to the flashx3 react app and type the following commands:
   - npm install express mongoose cors *required for server.js that shall be in the root of the project folder*
   - npm install jspdf *to enable pdf download*
   - 
3. In the react app, add the files of src and public folder of this github repository into the respective src and public folder in the flashx3 react app.

4. To run this project, type the following commands:
   (preferable to open the project folder in VS code)
   Open terminal:
   - cmd
   - node server.js
   *This establishes the backend connection*

   Open another terminal (using the + button in the top right corner in VS code):
   - cmd
   - npm start
   *This establishes the frontend connection*
