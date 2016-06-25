#Jeff Bentley - The Capstone Project
June 25, 2016

##Product Name
The name of my application is Running Notes.

##Product Overview
Running Notes is an HTML Word Processor that lives in your browser as a tab. You will be able to switch to it to take quick notes for research or study thereby not interrupting your workflow by having to leave your browser. It will also open showing the last 3 recent notes and be able to search your notes for keywords or by date. Other features will be added as time allows. 

##Specific Functionality
Running Notes will need to have a way to install itself as a browser tab. A Python script should be able to perform this task. There is currently a way to have this page launch on startup as a tab. I will also create the Running Notes logo for the tab using CSS and HTML. Running Notes will open with the current date in the active window which will be to the right(see mockup drawing)[Window Mockup Drawing](https://www.draw.io/#G0Bw0IpoGft_4TMmJKYXBMekRqUXM). The last 3 recent notes will open in the left column pane. There will be a search bbar at the right on the top pane. The app will also be able to seave the current state of the file. This state will be stored in a SQL database for retrieval. Text searching will be accomplished using PostgreSQL as recommended by the instructor. 

##Data Model
The app will use a save state field that can be initialized at app launch to display the current date on the right active pane and the last 3 most recent notes on the left pane. The search field will have PostgreSQL capability and display the state interface with HTML. If time allows there will be a subject field for notes sorted by category. The optional top left category pane(see mockup drawing)[Window Mockup Drawing](https://www.draw.io/#G0Bw0IpoGft_4TMmJKYXBMekRqUXM).

##Technical Components
The Python script for automating the tab install on the browser will be the biggest technical challenge initially. This will need to also go out and grab the CSS styling and HTML code to display the opening page after opening the browser. The second main function is integration of the PostgreSQL text search with the Django SQL. I am still researching this, I may be able to just use PostgreSQL instead.

##Schedule
The Python script for automated install of the tab on startup and launch that will populate the page with fields. This hard task will take a week.
Integrate PostgreSQL functionality into the app with the search function and search by keyword or date. This will take a week or more.
