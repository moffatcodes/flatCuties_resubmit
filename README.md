README.md
This is a simple README file for a web application that displays character information from an API. The application fetches data from a local server running on http://localhost:3000/characters and displays the character name in a span element on the webpage.

Setup
Clone the repository to your local machine.
Open the index.html file in a web browser.
Make sure you have a local server running on http://localhost:3000/characters to fetch character data.
The image element on the webpage will display the character's image using the characterOne.image property.
The character name will be displayed in the character-bar div element using the characterOne.name property.
The character's ID will be stored as a dataset on the span element for future use.

Usage
When the DOM content is loaded, the init function is called, which fetches character data from the local server and updates the webpage with the character's name and ID.
You can modify the code to display additional information or implement additional functionality based on your requirements.
License
This code is released under the MIT License. Feel free to use, modify, and distribute it as per the terms of the license.