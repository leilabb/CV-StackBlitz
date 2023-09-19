***CV App***

***Functionality*
User should be able to:
-Edit input fields with relevant information
-The state of the CV(the input fields) should be saved in between sessions (close or -update window)
-Add a new experience
-Remove an experience
-Update an existing experience
-Reorder the experiences
-Export the CV as pdf

Data structure:
-(CV is parent class or maybe App.js in this case)
-Header (class component)
-Experiences (class component): [id:,data:{}] 


Questions:
One CV or library of CV:s? One CV to begin with.
Different kind of experiences? Just one type of experience, so just one big list of experiences using the same template

***Design***
-Header section - Title, name, contact information
-Main section - Experience list'
-Buttons on top and bottom for exporting the CV
