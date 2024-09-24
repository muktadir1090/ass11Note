# ass11Note
Creating and saving Note as a Bussiness Owner

#Note Taker Application

##Description

The Note Taker application is designed for small business owners to write, save, and organize their thoughts or tasks. The application allows users to create, view, and manage notes, providing an intuitive interface for task tracking and thought organization.

##User Story

As a small business owner,
I want to be able to write and save notes,
so that I can organize my thoughts and keep track of tasks I need to complete.

##Acceptance Criteria

	•	GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page.
	•	WHEN I click on the link to the notes page
THEN I am presented with a page displaying existing notes in the left-hand column, and empty fields to enter a new note title and note text in the right-hand column.
	•	WHEN I enter a new note title and the note’s text
THEN a “Save Note” button and a “Clear Form” button appear in the navigation at the top of the page.
	•	WHEN I click on the “Save” button
THEN the new note I entered is saved, and it appears in the left-hand column with the other existing notes. The buttons in the navigation disappear.
	•	WHEN I click on an existing note in the left-hand column
THEN that note appears in the right-hand column, and a “New Note” button appears in the navigation.
	•	WHEN I click on the “New Note” button in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and note text, and the button disappears.

Features

	•	Create, edit, and save notes.
	•	View a list of existing notes in the left-hand column.
	•	Save new notes with a “Save Note” button.
	•	Clear current form fields with a “Clear Form” button.
	•	View the content of existing notes by clicking on them.
	•	Create a new note using a “New Note” button.


##Installation

To install and run the application locally:

	1.	Clone the repository:

    git clone <repository-url>

	2.	Navigate to the project directory:
    cd note-taker-app

	3.	Install the required dependencies:
       npm install


	4.	Start the application:
        npm start

##Usage

Once the application is started, you will be presented with a landing page that has a link to the notes page. Navigate to the notes page, where you can create, view, and manage your notes.

##Technologies Used

	•	HTML
	•	CSS
	•	JavaScript
	•	Node.js (if using server-side implementation)
	•	Express.js (optional, if applicable for server-side)
	•	Local Storage or Database for note persistence

##License

This project is licensed under the MIT License. See the LICENSE file for more details.

Feel free to modify the installation or other details to fit your specific implementation of the project!
