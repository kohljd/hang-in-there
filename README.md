# Hang In There

## Set Up

1. Fork this repository
2. Clone down your new, forked repo
3. `cd` into the repository
4. Open it in your text editor
5. Add the instructors as collaborators on the repository

Project spec & rubric can be found [here](https://curriculum.turing.edu/module2/projects/hang_in_there/)

To view your project:

1. In your terminal, navigate to your project repo
2. Run the command `open index.html`
  
______________________________________________________  
# README Template  
Before turning this project in, erase this line and everything above it and fill in the info below.  
______________________________________________________  

# Hang in There  

### Abstract:
[//]: <> (Briefly describe what you built and its features. What problem is the app solving? How does this application solve that problem?)

### Installation Instructions:
[//]: <> (What steps does a person have to take to get your app cloned down and running?)

### Preview of App:
[//]: <> (Provide ONE gif or screenshot of your application - choose the "coolest" piece of functionality to show off. gifs preferred!)

### Context:
[//]: <> (Give some context for the project here. How long did you have to work on it? How far into the Turing program are you?)

### Contributors:
[//]: <> (Who worked on this application? Link to your GitHub. Consider also providing LinkedIn link)

### Learning Goals:
[//]: <> (What were the learning goals of this project? What tech did you work with?)

### Wins + Challenges:
[//]: <> (What are 2-3 wins you have from this project? What were some challenges you faced - and how did you get over them?)

### Iteration 0
- [x] When the page loads, we should see a poster with a randomly selected image, title, and quote
- [x] Every time the user clicks the Show Random Poster button, a new random poster is displayed.

### Iteration 1
- [ ] When a user clicks the “Make Your Own Poster” button, we should see the form, and the main poster should be hidden
- [ ] When a user clicks the “View Saved Posters” button, we should see the saved posters area, and the main poster should be hidden
- [ ] When a user clicks the “Nevermind, take me back!” or “Back to Main” buttons, we should only see the main poster section

In summary: Be able to switch between the three views (main poster, form, and saved posters) on the correct button clicks

### Iteration 2
- [ ] On the new poster form view, users should be able to fill out the three input fields and then hit the Show My Poster button
- [ ] When the Show My Poster button is clicked, several things will happen:
  - [ ] Use the values from the inputs to create a new, unique poster object (part of your data model)
  - [ ] Save the submitted data into the respective arrays (image URL into the images array, etc - all part of your data model) so that future random posters can use the user-created data
  - [ ] Change back to the main poster view (hiding the form view again)
  - [ ] Use the new, unique poster object (part of your data model) to display the newly created poster image, title, and quote in the main view on the DOM

### Iteration 3
- [ ] When a user clicks the “Save This Poster” button, the current main poster will be added to the savedPosters array.
- [ ] If a user clicks the “Save This Poster” more than once on a single poster, it will still only be saved once (no duplicates)
- [ ] When a user clicks the “Show Saved Posters” button, we should see the saved posters section
- [ ] All the posters in the savedPosters array should be displayed in the saved posters grid section

### Iteration 4
- [ ] From the saved posters view, if a user double clicks a saved poster, it will be deleted
  - HTML onclick attributes should not be used in any HTML code - all functionality should be through JavaScript.

### Optional Extensions
- [ ] Implement data validation and error handling into the form (disable button, provide error messages if data entered is not correct, etc)
- [ ] In the main poster view, allow users to click each piece of the poster (image, title, quote) to update just that piece with another random item from the appropriate array
- [ ] When a user single clicks a saved poster, create a modal to view it larger
- [ ] Allow users to drag and drop saved posters into whatever order they want them to appear
