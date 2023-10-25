# Title: Game of Thrones
URL to Webpage: https://srizaaryal.github.io/gameofthrones/
URL to React Code on GitHub: https://github.com/srizaaryal/gameofthrones.git


# Background on the project: 
The project revolves around a Game of Thrones website with three main pages: Home, Characters, and Houses.

The Home page provides information about the background and context of the Game of Thrones series.

The Characters page features a list of prominent characters. When users click on a specific character, it provides detailed information about that character if available.

The Houses page showcases a list of featured houses. Clicking on a red-colored button reveals the name of the house's landlord. Grey-colored buttons do not have a landlord's name associated with them.

# Implemented Features

## Navigation Bar
#### Description: 
The Navigation Bar is prominently located at the top of the page and contains links to three main components: Home, Characters, and Houses. This allows users to easily access and navigate between different sections of the website.
#### Why: 
The Navigation Bar enhances user experience by providing a clear and accessible means of moving throughout the site. Users can swiftly switch between the main sections, ensuring a seamless browsing experience.

## AppRoute Component
#### Description: 
The AppRoute Component is an integral part of the navigation system, defining paths and their corresponding elements. It is responsible for directing users to the appropriate content when they click on links within the Navigation Bar.
#### Why: 
The AppRoute Component is essential for proper routing and content delivery. It ensures that when users click on links like "Home," "Characters," or "Houses" in the Navigation Bar, they are taken to the relevant sections of the website. This makes for efficient and logical navigation, contributing to a more user-friendly and intuitive web experience.

## Home Page:
#### Description: 
The Home Page provides background information about the Game of Thrones series.
#### Why: 
I included this feature to offer users a brief introduction to the world of Game of Thrones, making it more engaging and informative.

## Characters Page:
#### Description: 
The Characters Page displays a list of featured characters and allows users to click on a character to access additional information.
#### Why: 
I included this feature to help users explore the rich character universe of Game of Thrones and learn more about their favorite characters.

## Houses Page:
#### Description: 
The Houses Page showcases a list of featured houses, indicating the landlord for houses with available information.
#### Why: 
I included this feature to allow users to delve into the noble houses of Westeros, providing insight into their leadership and history.

## Character Information:
#### Description: 
Detailed information is available for each character, including their backstory, relationships, and notable actions.
#### Why: 
This feature enhances user engagement by providing comprehensive character profiles, enriching the Game of Thrones experience.

House Landlord Information:
#### Description: 
For houses with landlords, the landlord's name is provided, offering a deeper understanding of the power structure.
#### Why: 
Including landlord information adds depth to the depiction of noble houses and their leadership.

## Color-Coded Buttons:
#### Description: 
Red buttons indicate houses with landlords, while grey buttons represent houses without known landlords.
#### Why: 
Color-coding visually conveys whether a house has a known landlord, aiding user navigation and information retrieval.

## Pagination:
#### Description: 
The Pagination component is implemented on the Characters and Houses pages, allowing users to easily change the page number, thereby displaying new sets of characters and houses in lists.
#### Why: 
With the extensive number of characters and houses in the Game of Thrones universe, presenting them all on a single page would be overwhelming and challenging for users to navigate. To enhance user experience, Pagination has been integrated to limit the display to 24 characters and houses per page, making it more manageable and user-friendly.


# Standard User Flow
This section will walk you through the typical steps a user would take when navigating your Game of Thrones website:

Initial Landing on the Home Page
Users start by landing on the website's Home Page. Here, they can read about the background and context of the Game of Thrones series.

Exploring Characters
If a user is interested in learning more about the characters from the series, they can click on the "Characters" link in the Navigation Bar.
This action takes them to the Characters Page, which features a list of prominent characters.
Users can click on a specific character's name to access additional information about that character, including their backstory, relationships, and notable actions.

Discovering Houses
For users interested in the noble houses within the Game of Thrones universe, they can click on the "Houses" link in the Navigation Bar.
This action directs them to the Houses Page, which showcases a list of featured houses.
By clicking on a house's name, users can learn more about the house and its landlord, if available.

Pagination for Large Lists
Given the extensive number of characters and houses, pagination is implemented.
Users can change the page number to view different sets of characters and houses.
The system displays only 24 characters and houses per page, making navigation and information retrieval more manageable.

Seamless Navigation with Navigation Bar
At any point in the user flow, users can easily return to the Home Page, Characters Page, or Houses Page by using the Navigation Bar at the top of the page.
The Navigation Bar ensures effortless and efficient movement between different sections of the website.

AppRoute for Routing
Behind the scenes, the AppRoute Component ensures that users are directed to the correct content when they click on links within the Navigation Bar.
This essential component defines paths and their corresponding elements, making sure the user ends up in the right place.

# The API:
An API of Ice And Fire is the world's greatest source for quantified and structured data from the universe of Ice and Fire (and the HBO series Game of Thrones). This API provides access to data about all the Books, Characters and Houses in an easy to use JSON format.
The API URL is https://anapioficeandfire.com/ 


# Technology Stack
This website was developed using a specific technology stack to ensure efficient functionality and a seamless user experience. Below, here is the outline of the key components of technology stack:

## Front-End:

#### HTML (Hypertext Markup Language): 
The foundation of our website's structure and content.
#### CSS (Cascading Style Sheets): 
Responsible for the website's layout and visual styling.
#### JavaScript: 
Used for interactivity, dynamic content, and enhancing user experience.
#### React: 
A JavaScript library for building user interfaces, which enabled the creation of dynamic and responsive web pages.

## Back-End:
#### Node.js: 
A JavaScript runtime that facilitated server-side scripting.
#### Express.js: 
A Node.js web application framework used for routing and handling server requests.

## GitHub: 
The platform where our code repository is hosted, allowing for collaborative development and code management.

## Dependencies and Packages:
axios, react, react-dom, react-dom-router, react-scripts. 
