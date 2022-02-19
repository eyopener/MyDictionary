# MyDictionary
A Chrome Extension

# Contributors
Muskan https://github.com/eyopener

# About the Project
This Chrome Extension allows the user to search meaning of word. It provides examples , synonyms , antonyms of the searched word for better understanding . 
It helps the user to know the correct pronounciation of the searched word. All this can be achieved on the same tab.

# Project Repository
 https://github.com/eyopener/MyDictionary

# ⚒️ Tech Stack
JavaScript , HTML5 , CSS3 , git , Visual Studio Code 

# API Used
 https://api.dictionaryapi.dev/api/v2/entries/en/earth
 
 This API is used to fetch the neccessary details that showed in our project.

# Week-Wise Progress
## Week 1

### OBJECTIVE :
 An extension adds features and functions to a browser. It's created using familiar web-based technologies—HTML, CSS, and JavaScript. It can take advantage of the same web APIs as JavaScript on a web page, but an extension also has access to its own set of JavaScript APIs.

### COMMON GOALS :
 They enable users to tailor Chrome functionality and behavior to individual needs or preferences. They are built on web technologies such as HTML, JavaScript, and CSS. An extension must fulfill a single purpose that is narrowly defined and easy to understand.

### Explored various Preliminary resources and  learned about Open Source Contribution.

## Week 2

### SETUP DEVELOPMENT ENVIRONMENT :
To load your extension: Open Chrome browser and navigate to chrome://extensions. Enable Developer Mode by clicking the toggle switch next to Developer mode. Click the LOAD UNPACKED button and select the extension directory.

### STARTING WITH THE PROJECT :
Extensions are made of different, but cohesive, components. Components can include background scripts, content scripts, an options page, UI elements and various logic files. Extension components are created with web development technologies: HTML, CSS, and JavaScript. An extension's components will depend on its functionality and may not require every option.
#### Create the manifest : 
Extensions start with their manifest. Create a file called manifest.json
#### Load an unpacked extension :
-> The directory holding the manifest file can be added as an extension in developer mode in its current state. To load an unpacked extension in developer mode, follow these steps:

-> Open the Extension Management page by navigating to chrome://extensions.

-> Alternatively, open this page by clicking on the Extensions menu button and selecting Manage Extensions at the bottom of the menu.
-> Alternatively, open this page by clicking on the Chrome menu, hovering over More Tools then selecting Extensions

-> Enable Developer Mode by clicking the toggle switch next to Developer mode.

->Click the Load unpacked button and select the extension directory.
Loading an unpacked extension

## Week 3 && Week 4

### Continue Project Work

-> Add functionality
The extension is now installed, but it doesn't currently do anything because we haven't told it what to do or when to do it. Let's fix it.

-> Chrome to present it in the extension's popup. To do this, add an action object to the manifest and set index.html as the action's default_popup.

-> The index's HTML references an external CSS file named Styles.css. Add another file to the extension's directory, name it appropriately.

-> The extension now has a custom icon and a index, and it colors the popup button based on a value saved to the extension's storage. Next, it needs logic for further user interaction. Update Script.js.

-> The updated code adds a click event listener to the button, which triggers a programmatically injected content script. 
The manifest will need the activeTab permission to allow the extension temporary access to the current page.

## Week 5

-> Started working on the Project Report.

## Week 6
-> Finally, Wrapping up of the Project. Completed Project Report and Showcased project to our Mentor.

# Conclusion
It is a small program to modify the experience or add functionality to the chrome browser. They are created using web technology like HTML, CSS, JavaScript, etc. ... An extension should have the minimal interface or it can extend to a web page also but main focus is to provide good functionality with less overhead.

# Future Scope
Creating a custom Google Chrome extension is a great way to improve your browser functionality and create optimal user experiences.
