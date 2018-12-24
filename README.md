Project:
Use HTML, CSS and, the Google Chrome built in Dev Tools to replicate the google home page. The links won't go anywhere and the forms won't do anything.

Goals:
- Practice using, and become comfortable with HTML, CSS and Dev Tools
- Develop a polished product
- Learn how to update code and properties live within the Dev Dools framework
- Learn about favicons and how to apply one

Post Project Reflection:
- favicons:
    - The little pictures in the tabs of your web browser
    - Below is an example of how you apply them
        - <link rel="icon" type="image/ico" href="https://www.google.ca/favicon.ico">
        - The href link can be a locally saved image with the .ico file extension or a link to a .ico online (just like other images)
        - In practice it should be hosted on your website (just like any other image) because websites controlled by others can change which willl break your links 

- flex boxes are good ways to organize data
    - There are a few dificulties with them and can create the need for debugging time
    - The flex boxes need a container, this should be the parent component or div for the flex boxes
    - The container is where you define how the boxes interact (spacing, text alignment, etc..)
    - The flex boxes themselves are where you define content, they are individual components or divs, can have nested div elements as your flex boxes, however only the children of the container will be a flex box

- Different values for position (ex. absolute, relative, etc...) all work differently and can have different keywords required for defining their positions
- Use % for dynamic positioning of items based on page size (ie. if you want the footer to always apear on the screen then setting the top value as something like 95% will push it down to the bottom 5% of the page no matter the page size)
- Buttons can be setup as images by including the <img> tag with full definitions between the fully defined <button> and </button> tags
    - Links can be setup as images the same way as listed above, but you should use the link tags <a> and </a> instead of the button tags
- Classes are good ways to define multiple sets of data the same way
    - If there is a chance that you will use the same format multiple times you may aswell define it as a class instead of an id, that way you don't need to worry about it later when you try to reuse it

- Developer tools:
    - Using the Computed tab instead of the Styles tab will allow you to see which rules are prevailing, from there you can expand the computed style, and narrow into where that is being defined in the CSS, this can help with determining why an unexpected style is coming up
    - Using the select an element tool can help you narrow into what HTML is defining an element, from there you can find the div, and class/id defining the item and then in turn the associated CSS under the styles tab
    - You can use the toggle element state tool to turn on an element state, and then use the computed and styles tabs to drill down into what is causing the element state, or what the styles are for that element
    - You can input code directly into the developer tool to see the webpage change dynamically, this is usefull when you are trying to change positions to see the optimal location, or when you are trying to debug (ie. any time that you are making small changes and refreshing frequently)