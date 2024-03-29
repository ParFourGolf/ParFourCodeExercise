# Coding Exercise: Simple Note-Taking App

Your task is to create a simple note-taking app using React Native. This is intended to take less than 15 minutes and serve as a basis for conversation.  There is no need to spend extra time on complexity.

You can clone this repo or create your own using:

```
npx create-expo-app -t expo-template-blank-typescript
```

# Features
1. **Typescript:** Use Typescript in all files you create. Make sure to define types for your state, props, event handlers, and any other values that can be typed. Use interfaces or types to define the shape of objects, and use enums where appropriate. This will help ensure that your code is type-safe and easy to understand.
   
2. **Note Input:** The app should provide an input field that allows users to enter a note.

3. **Add Button:** There should be an "Add" button. When this button is pressed, the app should add the note to the existing notes and clear the input field.

4. **Note Display:** The app should display all entered notes below the input form.

5. **React Native UI Components:** The app should be built using only React Native UI components.

6. **Separation of Concerns:** The business logic and state management of the app should be handled in a separate file. Similarly, all data storage-related logic should be in a separate file. The input field state can be stored anywhere.

7. **Styling:** Style the app similarly to the provided screenshot. Exact matching is not required. Feel free to add a bottom margin to achieve spacing between elements.  There is no need to create a more complex spacer component.

![alt text](screenshot.png "Screenshot")
