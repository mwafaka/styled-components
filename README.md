
### Task 1 📋

The profile card currently has a default margin value of `150px auto`. Modify the `StyledProfileCard` component to use a default margin value of `100px auto` instead.

### Task 2 🎨

Add a new prop called `backgroundColor` to the `StyledProfileCard` component. This prop should allow customization of the background color of the card. The default background color should be `#f5f5f5`.

### Task 3 💼

Create a new styled component called `StyledProfileImage` to represent the profile image of the card. Apply the following styles to the `StyledProfileImage` component:
- Set the border radius to `50%`.
- Set the box shadow to `0 2px 5px rgba(0, 0, 0, 0.1)`.

### Task 4 📝

Modify the `StyledProfileName` component to have a font size of `20px` and a margin-bottom of `10px`.

### Task 5 📞

Create a new styled component called `StyledContactButton` to represent a contact button on the profile card. Apply the following styles to the `StyledContactButton` component:
- Set the padding to `10px`.
- Set the background color to `#1e90ff`.
- Set the color to `#fff`.
- Set the border to `none`.
- Set the border-radius to `5px`.
- Set the cursor to `pointer`.

### Task 6 🖊️

Create a new component called `ProfileCard` that wraps the `StyledProfileCard`, `StyledProfileImage`, `StyledProfileName`, and `StyledContactButton` components. The `ProfileCard` component should accept the following props:
- `margin`: A string representing the margin value for the card.
- `backgroundColor`: A string representing the background color of the card.

Inside the `ProfileCard` component, render the following:
- A `StyledProfileImage` component representing the profile image.
- A `<h2>` element with the name of the person.
- A paragraph element with a short bio.
- A `StyledContactButton` component with appropriate text.

### Task 7 ✨

Export the `ProfileCard` component as the default export of the module.

---





Good luck! 🚀
