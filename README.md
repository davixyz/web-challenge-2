# web-challenge-2

Welcome to this Web Challenge! we will be using:

- HTML
- CSS
- JS
- React

## Challenge: Text Styler MVP

We want to build a minimum value product for a text styler where we can select a style option, write some text, and display the styled text on the screen.

Here's an example of the end product:
<br /><br />
<img src="https://res.cloudinary.com/carlosdev/image/upload/v1643522524/web-challenge/textStylerWithValues_ckessi.png" width="400"/>

## Functionality

- Users can select a single style at a time
- We need style options for Bold, Italics, and a Custom one you like, for example, Red and Bolded
- Users can enter the text on an input field
- Users should be able to see the styled text in a box below the input field
- Assume that the user will enter and delete one word at a time

## Out of Scope

- Copy-Pasting
- Deleting Multiple characters
- Pixel Perfect Styles
  - This is your exercise; style it how you want.

## Video of the Functionality

https://user-images.githubusercontent.com/4756314/151688778-d0848bad-ef33-4307-9ca1-e824ada25816.mp4


## Reference UI Screen

<img src="https://res.cloudinary.com/carlosdev/image/upload/v1643522373/web-challenge/textStyler_wkgxlp.png" width="480"/>

## Tips and Notes

- The project uses standalone babel, so assume React and ReactDOM are in the global window scope. For example, to import a hook from React, you can do:

```js
const { useState } = React;
```

- If you want to achieve the same styles as the pictures/video, CSS Flex API will be your friend.
- Start focusing on the logic first and style later.
  - How can you make reusable components?
  - What data structures will you use for the state?
  - How do you keep track of new characters added and their styles?
  - How can you make the styling behavior generic to add more options without making too many code changes?
- [Input radio buttons](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/radio) can help you for having a single selection value at a time
- You most likely will need state, the [React State and Lifecycle documentation](https://reactjs.org/docs/state-and-lifecycle.html) help you understand those concepts better
- Have fun!
