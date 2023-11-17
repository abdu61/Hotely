#### IMP Note: 
This is a Demo Project for ITSE 476 Open Source Project. The code and everything here is demo as part of the Course to learn about open source projects.  



# Hotely App
The Hotely App is open-source project on Github. Its a free software application that allows Customer to Book, Check-in, and Pay for Rooms Hotels While Hotel Staffs can use for Room Availability Management, Perfomance Analytics etc. 



## License
This project is **open source** and licensed under the MIT License. This means that anyone can use, modify, and distribute this project for any purpose, as long as they give credit to the original author and include the license notice. This project is free and open for everyone to contribute and collaborate.

## First Look Around
Since our Topic is Hotel Management its one of the most popular topic and there are lot of Open Source Project out there. We proceeded anyway because we are using for education purpose. And since we actually learning from each process on how open source development works and even in general about github. And we did find many project for our topic. And here are some:

- <a href="https://github.com/webkul/hotelcommerce">https://github.com/webkul/hotelcommerce</a>
- <a href="https://github.com/HouariZegai/HotelReservationSystem">https://github.com/HouariZegai/HotelReservationSystem</a>

## How we choose the Name
Choosing Name was one of the difficult part for us. Especially since whatever name we come up with hit on some end. As most of the domain is already taken and we can't simply use generic topic. We neede the name to be unique at the same time it should explain itself what the App was related to. And we come up with "Hotely". This perfectly fit for our project and ticked all our requirements. It was a surprise for us that this name was not already taken especially since it explain itself and also rhyme similar to "Hotel". 



## Features and Requirements List:
#### Functional Requirements:
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


#### Non-functional Requirements:

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


#### User stories

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
For open source projects, GitHub offers free public version control hosting. This involves creating an online, publicly accessible version controlled repository from which anybody may view the project's resources and get updates. For both users and developers, a version control repository indicates that the project is trying to provide resources so that everyone can contribute.GitHub is a reasonable option for the majority of projects, even though it's not the sole or even the best one.The project's bug tracker is in the same boat. A bug tracking system's value extends beyond its regular utility to developers to include the implications it holds for project observers. An accessible bug database is, in the opinion of many, one of the most compelling indicators that a project should be.



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



## Develper Documentation:
You can refer to Documentation and Developer guidelines along with this. Here we will deep dive into how our whole process works:

#### Contribution
To contribute to the app, you can follow these steps:
-	Fork the open source Ionic app repository on GitHub and clone it to your local machine.
-	Create a new branch for your feature or bug fix, named as feature/<feature-name> or bugfix/<bug-id>, and branch off from the develop branch.
-	Write your code and tests, following the coding standards and conventions of the project.
-	Commit and push your changes to your forked repository, using clear and descriptive messages.
-	Create a pull request to merge your branch into the develop branch of the original repository. The pull request should have a clear and descriptive title and a detailed description of the changes. You should also assign a reviewer to review your code and approve the merge.

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

#### Bug Tracking Process:
If you found a bug. You can quickly create a issue by following
- Goto "Bug fix" Branch. If it severe/critical Goto "hotfix" branch
- Raise a issue with all the details. It would be better to give detailed information
- Additionally you can chat through Discord after raising a issue this way our developers and community will know the bug better and come up with a fix




## User Characterstics and Screenshots:
### Characterstics:
##### Our system has three types of users
1. Customer Group:
customers book Rooms, Check-in, Payment and offer feedback by interacting directly with our App. We do keep a little amount of consumer data on file in our Database. After customer booked a room.
2. Hotel staffs:
Hotel Staff can manage all the booking, look for vacancies, book a room at desk, look at Food invetory for rooms etc. The hotel staff name, address, speciality, and other details are kept in the database.
3. Admin:
The administrator's job is to manage the whole App it gives all details and analytics about both staff and customers it also gives the revenue and expense reports.
 
### Screenshots:
- Login Page
<img src="img\Picture1.png" width="350">
<br>
- Hotel Page
<img src="img\Picture2.png" width="350">





## Hosting:
Hosting is the location where the project is kept accessible to all. Since GitHub is one of the popular platform to host open source projects, we will host it there so that users and developers may access it and provide us with comments. 



## Codes of Conduct:

This code of conduct outlines our expectations for participants within our project, as well as steps to reporting unacceptable behavior. We are committed to providing a welcoming and inspiring community for all and expect our code of conduct to be honored. Anyone who violates this code of conduct may be banned from the project.

#### Our Pledge
Our project is dedicated to creating a positive and inclusive environment for everyone, regardless of gender, gender identity and expression, age, sexual orientation, disability, physical appearance, body size, race, ethnicity, religion (or lack thereof), or technology choices. We do not tolerate harassment of project participants in any form, online or offline.

## Our Standards
Examples of behavior that contributes to creating a positive environment include:
-	Using welcoming and inclusive language
-	Being respectful of differing viewpoints and experiences
-	Gracefully accepting constructive criticism
-	Focusing on what is best for the project and the community
-	Showing empathy and kindness towards other project participants
Examples of unacceptable behavior by participants include:
-	The use of sexualized language or imagery and unwelcome sexual attention or advances
-	Trolling, insulting or derogatory comments, and personal or political attacks
-	Public or private harassment
-	Publishing others’ private information, such as a physical or email address, without their explicit permission
-	Other conduct which could reasonably be considered inappropriate in a professional setting

#### Our Responsibilities
The project maintainers are responsible for clarifying the standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.

The project maintainers have the right and responsibility to remove, edit, or reject comments, commits, code, wiki edits, issues, and other contributions that are not aligned to this code of conduct, or to ban temporarily or permanently any contributor for other behaviors that they deem inappropriate, threatening, offensive, or harmful.

#### Scope
This code of conduct applies both within project spaces and in public spaces when an individual is representing the project or its community. Examples of representing a project or community include using an official project e-mail address, posting via an official social media account, or acting as an appointed representative at an online or offline event. Representation of a project may be further defined and clarified by project maintainers.

#### Enforcement
Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting the project team at <a href='20192028@stu.uob.edu.bh'>Email</a> . All complaints will be reviewed and investigated and will result in a response that is deemed necessary and appropriate to the circumstances. The project team is obligated to maintain confidentiality with regard to the reporter of an incident. Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the code of conduct in good faith may face temporary or permanent repercussions as determined by other members of the project’s leadership.

#### Attribution
This code of conduct is adapted from the Contributor Covenant, version 2.1, available at https://www.contributor-covenant.org/version/2/1/code_of_conduct.html.



## Announcing
Announcing the project and letting people know about the project is one of the most critical part of the project. So its important to announce publicly in the landing page of project and in open source communities. Since our porject is part of the course and its a demo project we will just soft launch the project and will be making the Repository private after correction.


## FAQ
We will address some common questions and concerns here.

- Q: How can I report a bug or issue?<br>
A: If you encounter a bug or issue, please refer to Bug Tracking under <a href="https://github.com/abdu61/Hotely#version">Version Control and Bug Tracking</a>. Include as much detail as possible, such as steps to reproduce the issue and your operating system/environment.

- Q: Can I request a new feature or enhancement?<br>
A: Absolutely! We encourage users to suggest new features or enhancements. You can goto our feature branch. Create a New Issue Request which will be pinged to our discord. In discord all communication take place including wheather to Develop or Discard. When creating a issue Clearly describe the proposed feature and explain how it would benefit the project.

- Q: How can I contact the project maintainers?<br>
A: You can reach out to the project maintainers by Discord or <a href="20192028@stu.uob.edu.bh">Email</a>.

- Q: Can I redistribute or modify the project?<br>
A: Absolutely. We use MIT Licence. So go fork out the project and create your own. We absolutely love to see what our community builds.



