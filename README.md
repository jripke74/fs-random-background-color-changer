# fs-random-background-color-changer

Debug a Random Background Color Changer
Build an app that is functionally similar to this example project. Try not to copy the example project, give it your own personal style.

Camperbot is learning JavaScript and has tried to build their own Random Background Color Changer. However, they have made a few mistakes along the way.

Fulfill the user stories below and get all the tests to pass so the lab is functioning properly.

User Stories:

1. You should fix the syntax errors in the darkColorsArr array.
2. You should fix the ReferenceError thrown when the math object is referenced inside the getRandomIndex function.
3. You should round down randomIndex to the nearest whole number.
4. You should update the value of the body variable to use the correct method name and fix the related TypeError.
5. You should fix bgHexCodeSpanElement so that it correctly selects the element with the id of bg-hex-code.
6. You should modify the color variable inside changeBackgroundColor so that it is set to a random color from the darkColorsArr array.
7. You should update the btn variable so that it targets the button element. Open up the index.html to see the correct id name for that button element.
8. You should fix the line that adds an event listener for the click event to btn by passing a reference to the changeBackgroundColor function to the method.
9. Your background should randomly change to one of the colors in darkColorsArr each time the #btn is clicked.