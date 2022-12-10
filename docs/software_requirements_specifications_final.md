# Overview
This document contains the software requirements specification for our teams Mantra App. We have organized it via a collection of functional and non-functional requirements, sorted by general feature. This document will help clarify the specific functionality and performance of our application as we go to develop it.

# Functional Requirements

1. Navigation:
	1. The app shall respond to user touch in order to navigate the application. |TC01|
	2. The app shall display and contain a setting icon and a corresponding menu. 
2. Meditation Session Remaining Time:
	1. The app shall display the time remaining for the current meditation session. |TC03| 
	2. The app shall say a phrase to let the user know the session is over.
3. User Customization:
	1. The app shall allow the user to customize the length of their meditation session.
	2. The app shall allow the user the customize the displayed backround image. |TC02|
	3. The app shall display the user inputted text.
	4. The app shall 'read' over the specified text in the specified timing.
	5. The app shall play a sound in the specified timing.
	6. The user shall be able to change the specified timing. |TC01|
	7. The user shall be able to change the UI elements color. |TC01|
4. Settings Specific Functionality:
	1. The settings shall be expandable if requirements change or functionality is added. |TC01|
	2. The app shall include an option for different app layouts(Ex. Dark or Light mode). |TC01|
5. Base Mantra Funcionality:
	1. The app shall prompt the user to input their mantra. |TC01, TC04|
	2. The app shall display a start button to begin the session.
	3. The program shall include a personal achievement board for users to see where they are at and their progress with meditation.
	4. The program shall track the users time spent on the app, types of meditation used, and create meditation suggestions for the user.
	5. The program shall have a search function for different meditation techniques.


# Non-Functional Requirements

1. Stored Data:
	1. The app shall keep a history of the user’s past meditation sessions.
	2. The app shall store data locally to ensure privacy.
	3. The app shall be able to reuse mantras from users history 
2. Responsiveness:
	1. The app shall have a quick start up time with no set up required to get started.
3. Robustness:
	1. The app shall be robust in a way so that no standard user interactions with the app will compromise the functionality of the app or act unexpectedly.
	2. The app shall perform its functions without crashing.
	3. The app shall be able to jump from ios to android without any problems.
4. UX:
	1. The usability of the main features of the app shall be intuitive in a way that none or very limited tutorializing is necessary. 
	2. The interface such as any necessary tutorializing, settings, or main functionality of the reader, shall not be compromised and easily accessible from a default state and despite user input. (The user should not be able to softlock themselves from accessing or seeing the settings if they set the setting icon to black and the background to black for example.)
	3. The settings menu shall conform to standard usability guidelines.
	4. The program interface shall be easy to read and understand by the consumer.


