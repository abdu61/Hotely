#### Note: 
This is a Demo Project for ITSE 476 Open Source Project. The code and everything here is demo as part of the Course to learn about open source projects.  

# Hotely App
The Hotely App is open-source project on Github. Its a free software application that allows Customer to Book, Check-in, and Pay for Rooms Hotels While Hotel Staffs can use for Room Availability Management, Perfomance Analytics etc. 

## License
This project is **open source** and licensed under the MIT License. This means that anyone can use, modify, and distribute this project for any purpose, as long as they give credit to the original author and include the license notice. This project is free and open for everyone to contribute and collaborate.

## Features and Requirements List:
### Functional Requirements:
##### Online Booking (FR-001):
- Users must be able to browse available rooms, choose prefered dates, and make reservations online through the system.
- After a booking is successful, users should receive an email with reservation details.

##### Room Search and Filter (FR-002):
- It should be possible for users to look for available rooms using parameters like amenities, occupancy, and kind of room.
- A filtering mechanism is required by the system in order to fine-tune search results.

##### Check-in and Check-out (FR-003):
- It should be possible for guests to check in online before visiting the hotel.
- An electronic invoice must be generated as part of a streamlined check-out procedure supported by the system.

##### Feedback and Ratings (FR-004):
- It should be possible for visitors to rate and comment on their experiences using the system.
- The hotel's management must be connected to the feedback mechanism for continuous improvement.


### Non-functional Requirements:

##### Performance (NFR-001):
- Under normal operating conditions, the system must react to user interactions in 3 seconds or less.
- At least 500 users should be able to access it concurrently without experiencing a noticeable drop in performance.

##### Security (NFR-002):
- Industry standards for user authentication and authorisation must be followed to protect sensitive personal and financial data.
- Sensitive data should be encrypted by the system both during storage and transmission.

##### Scalability (NFR-003):
- Within the next year, there should be a 20% increase in user load, and the system architecture needs to be scalable to handle this.
- Without requiring significant architectural modifications, it ought to allow the addition of new features and modules.

##### Availability (NFR-004):
- Users should be able to access the system continuously with an uptime of at least 99.9%.
- To reduce interruptions, routine maintenance and updates should be planned for off-peak times.


### User stories

- <b>Check-in Process:</b>
As a hotel guest, I want to check-in seamlessly, either online or at the front desk, so I can quickly access my room upon arrival. The process should be user-friendly and provide necessary information.

- <b>Feedback Submission:</b>
As a hotel guest, after my stay, I want to provide feedback on my experience, including ratings and comments. This will help the hotel improve its services and assist future guests in making informed decisions.

- <b>Room Reservation:</b>
As a guest, I want to reserve a room for my upcoming stay, so I can plan my visit in advance. I should be able to select the dates, room type, and any specific preferences.

- <b>Room Availability Management:</b>
As a hotel manager, I want to view and manage the availability of rooms in real-time. This includes updating the status of rooms (clean, occupied, vacant), making adjustments to reservations, and ensuring accurate information for potential guests.

- <b>Performance Analytics:</b>
As a hotel manager, I want access to performance analytics and reports, such as occupancy rates, revenue generated, and popular room types. This will aid in decision-making, allowing me to optimize pricing strategies and allocate resources effectively.

## Development Status:
 #### ACTIVE DEVELOPMENT  - middle of development of beta  
- The system has reached the end of its basic design and initial functionality. 
- The project is still being put into action, though. However, the entire project will be attempted to be implemented by developers and other contributors who are willing to join us.
- Up until the completion of the project, each implemented function will be published to the repository


## Downloads:
- <b>Node.js:</b>Its a Javascript runtime environment that is required to run ionic . Link: https://nodejs.org/en/download/
- <b>Ionic CLI:</b> Ionic projects can be created, built, and executed using the Ionic command-line interface. Using your terminal or command prompt, type the following command to install it: npm install -g ionic
- <b>Firebase CLI:</b> Using the command line, users can communicate with Firebase services through the Firebase command-line interface. Using your terminal or command prompt, type the following command to install it: npm install -g firebase-tools
- <b>Git:</b> Git is a version control that we use to track and collaborate project. Link: https://git-scm.com/downloads


## Version Control and Bug Tracking



## Communication Channels:
As for any project communication is one of the backbones of the project. And we use mainly two platforms **Github issues** and **Discord**.
-	GitHub Issues: This is a built-in feature of GitHub that allows users to report bugs, request features, ask questions, and provide feedback on a project. GitHub Issues can be organized with labels, milestones, and projects, and can be linked to pull requests and commits. GitHub Issues are suitable for conversations that are related to the code and need to be tracked and resolved.

-	Discord: This is a chat and voice platform that allows users to create and join servers for various topics and communities. Discord can be integrated with GitHub using webhooks, bots, or services like Zapier to send notifications, updates, and commands for a project. We use Discord for every other communication including quick chat, future builds, more detailed interaction etc.


## Documentation
#### Pre-Requisites
Before you start working on the HMA, you need to have the following tools and accounts:
-	GitHub Account 
-	A Code Editor of your choice, such as VSCode
-	Web Browser
-	NODE.js and Ionic Framework installed in your PC
-	Added Plus is Discord (Our Communication Platform)
-	Account in firebase. As we use Firebase as our Database

#### Set-Up:
-	Clone or download the open source Ionic app repository from GitHub to your local machine.
-	Open the app folder in your code editor and run npm install to install the dependencies.
-	Create a file named firebase.config.ts in the src/environments folder and copy the Firebase configuration object from your Firebase project settings into it
-	Run ionic serve to launch the app in your browser. You should see the app homepage to login/create account.

#### Tutorial:
To book a Hotel with the app. follow this steps:
-	Login into App if not already done
-	Click Hotels in the Tab Bar (Default View)
-	Select from the hotel displayed or search with filters
-	Select Date and How many Guests. It will show the availability and price for the stay.
-	Click Book and Add Personal information such as Name and Contact Number. And select payment method. Then Click Confirm
-	You will get a receipt and confirmation mail for the same.

#### Known Issues:
This document is incomplete and may contain errors or inaccuracies. Some of the known issues are:
-	The App does not have any security validation
-	The App have issues with adapting to Tablet Screens



## Developer Guidelines:
This document provides best practices for developing, testing, and deploying the Hotel Management Application(HMA) on our GitHub. Whether you are beginner or experienced we got you covered on how to contribute to our Project.

#### Code Style and Formatting:
The HMA uses following languages:
-	HTML, CSS and JavaScript
-	Angular and Ionic Components

#### We use the following coding practice:
-	Format code with consistent spaces and indents. Use a tool like [Prettier] to do it automatically.
-	End statements with semicolons and avoid auto-insertion.
-	Name variables, functions, and classes clearly and descriptively. Use camelCase for variables and functions, and Pascal Case for classes.
-	Use single quotes for strings, unless you need double quotes for interpolation or escaping.
-	Use strict equality operators (=== and !==) to compare values, unless you need type coercion.
-	Enclose code blocks with braces ({}). Put the opening brace on the same line as the statement, and the closing brace on a new line.
-	Comment your code to explain its logic and purpose, especially if it is complex or not obvious. Use // for single-line comments and /* … */ for multi-line comments.
-	Use modern JavaScript features, such as let, const, arrow functions, template literals, and destructuring.

#### Branching and Merging:
The HMA uses ‘GitFlow’ workflow The Main Branches are:
-	main/master: Stable and production-ready code. Only authorized developers can merge into it.
-	feature: New features or enhancements. Each feature has its own branch, named as feature/<feature-name>, from develop.
-	bugfix: Bugs or errors. Each bugfix has its own branch, named as bugfix/<bug-id>, from develop.
-	hotfix: Critical bugs or issues in master. Each hotfix has its own branch, named as hotfix/<hotfix-id>, from master.

When you finish a feature or a bugfix, create a pull request to merge into develop. The pull request should have a clear title and description, and a reviewer to approve it.

#### Testing and Debugging:
-	Test your app with unit, end-to-end, and manual tests. Use tools like [Jasmine], [Protractor], or [Cypress] to write and run tests. Follow the [Arrange-Act-Assert] pattern and use code coverage tools.
-	Debug your app with browser dev tools, such as [Chrome DevTools] or [Safari Web Inspector], or code editors, such as [Visual Studio Code]. Use commands like [ionic serve], [ionic cordova run], [ionic capacitor run], [ionic doctor], and [ionic monitor] to run and debug your app on different platforms and devices.

#### Deployment and Maintenance:
We use tools and services to build, test, and deploy your app on different platforms and devices, such as:
-	<b>Appflow:</b> A cloud-based service to generate web and native builds, push live updates, publish to app stores, and automate the process.
-	<b>Ionic Advisory:</b> A service to get expert help and guidance for your Ionic development. Get tailored recommendations, active maintenance, and access to Ionic experts.


