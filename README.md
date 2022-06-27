## Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).


During the the full stack project development, there were a few different types of front end code that were used in different parts of the application. The customer facing site was developed originally in Express HTML and then converted over to a .hbs view to help with rendering speeds. HTML is static and client facing, which means it can't interact with backend databases to  update information. Javascript is a frontend and backend coding language that is used to add dynamic elements to the webpage. Using these allowed us to pull trip information from the MongoDB database, to ensure the page will change dynamically depending on what the user does.

# Why did the backend use a NoSQL MongoDB database?

The backend used a NoSQL MongoDB database because of its ease of modifying schema based on scaling and functionality changes, as well as the ability to rapidly scale horizontally because of its non-relational nature of the database.

# How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

JSON is a standardized way to format object data that can be easily read by Javascript to form it into a literal Javascript object. This ties frontend and backend development together by creating a way for data/ Javascript objects to be stored on the backend and used in different situations based on what the frontend is requesting the data for. 

# Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

An instance that code was refactored to improve functionality and efficiency is that the trip card versus trip list components. Having two seperate components that render the same information is inefficient, but having the each trip being rendered separately but part of the whole works better in the overall functionality.

# Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security.

There are a few ways of testing endpoints prior to adding security. One way is by just going to the localhost web address for the API endpoint to see if the page successfully loads the data or what type of error it throws if an error occurs.

# Explain your understanding of methods, endpoints, and security in a full stack application.


In a full stack application, the methods of the website is what drives the functionality and dynamics of a webpage. Methods like GET, POST, PUT, and DELETE are http requests that can be used to retrieve or modify the database so that the functionality can be implemented. Endpoints are the results of the methods as seen by the admin or the client side of the application. Endpoints should be tested so that they function how they should and display data properly or throw errors if an actual error occurs. Security is another layer of code that is added to prevent unauthorized or unauthenticated users from accessing or modifying te database.

# How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

This course has helped me narrow down the direction I want to go career wise and what other skills I need to pursue to be competitive in the job market. I think that the biggest skill that I have developed in this process is that I have gained a better understanding how different modules or components of code link together and how they can be used to build a finished product. I enjoyed building this project piece by piece each week and seeing the final product.



