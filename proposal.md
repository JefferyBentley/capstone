#Jeff Bentley - The Capstone Project Proposal
July 5, 2016

##Product Name
The name of my application is Running Notes.

##Product Overview
Running Notes is an HTML Word Processor that lives in your browser as a tab. You will be able to switch to it to take quick notes for research or study thereby not interrupting your workflow by having to leave your browser. It will also open showing the last 3 recent notes and be able to search your notes for keywords or by date. A typewriter era textured paper look to the panes that are displayed. Other features will be added as time allows. 

##Specific Functionality
Running Notes will need to have a way to install itself as a browser tab. A Javascript function should be able to perform this task. There is currently a way to have this page launch on startup as a tab. I will also create the Running Notes logo for the tab using CSS and HTML. Running Notes will open with the current date in the active window which will be to the right(see mockup drawing)[Window Mockup Drawing](https://www.draw.io/#G0Bw0IpoGft_4TMmJKYXBMekRqUXM). The last 3 recent notes will open in the left column pane. There will be a search bar at the right on the top pane. The app will also be able to save the current state of the file. This state will be stored in a SQL database for retrieval. Text searching will be accomplished using PostgreSQL as recommended by the instructor. There will be autocomplete for searchs and throughout the application. A way to save a current note before starting a new note. will be added to the top left corner. It will have just one button. A User Id button will be added to the top right corner for login and authentication purposes. 

##Data Model
The app will use a save state field that can be initialized at app launch to display the current date on the right active pane and the last 3 most recent notes on the left pane. The search field will have PostgreSQL capability and display the state interface with HTML. There will be 2 database models. One will be Notes and the other will be Users. Under Notes the properties will be id, created_date, last_modified_date and note. A modal will be created for User authenication. User authentication is already built in to DjangoSQL. 

##Technical Components
The Python script for automating the user authentication will be the biggest technical challenge initially. This will need to also go out and grab the CSS styling and HTML code to display the opening page after opening the browser. The second main function is integration of the PostgreSQL text search with the Django SQL. I am still researching this, I may be able to just use PostgreSQL instead.

##Schedule
Javascript to install tab and and Running Notes icon on the browser tab on startup and launch that will populate the page with fields will be the first step. This hard task will take a week.

Secondly I will integrate PostgreSQL or DjangoSQL functionality into the app with the search function and search by keyword or date. I will also set up the Note and User Models and add the properties id, created_date and modified_date under the Notes model. This will take a week or more.

I will then work on the Javascript interactivity with the File and Save buttons and the clicks for opening recent notes and
also the search bar. This will have to integrate with the database also. This will take at least a week.

I will lastly work on the HTML and CSS styling for the panes and look and feel of the app. This will take another week.
Then final testing and full functionality verification with Chrome, Safari, Firefox and IE if there is time. 
Depending on how much time I have left I may add searching notes by subject or category. This will probably have to be decided earlier. So I may not implement this to keep the scope more focused. 

##Further Work
I will probably have a default font. Perhaps I can add more fonts and spell check features later. Future work would be change the color scheme and backgrounds. The ability to print your notes and email them as attachments may also be added. 
