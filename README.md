# React Autocomplete

You have an array of people. Implemented the Autocomplete component
using [Bulma Dropdown](https://bulma.io/documentation/components/dropdown/)
that will suggest people matching an entered text.

- suggestions should appear after some `delay` in typing (`debounce`);
- the `delay` should be customizable via props (default value is 300ms);
- show the list of all people when input is focused but empty ([Check this](https://mui.com/material-ui/react-autocomplete/#combo-box) to see how it can work)
- show `No matching suggestions` message if there are no people containing the entered text;
- don't run filtering again if the text has not changed (a pause in typing happened when the text was the same as before)
- save selected suggestion text to the input on click and close the list;
- pass the selected person to the `onSelected` callback passed via props;
- add an `h1` to the `App` showing `Name (born - died)` of the selected person or `No selected person`.
- when the selected person is displayed in the title, but the value in the input changes, the selected person should be cleared and `No selected person` should be shown.

## Demo Links

- [DEMO LINK](https://AndriiZakharenko.github.io/react_autocomplete/)
