### reading notes
* Responsively designed websites change fluidly depending on a variety of factors, such as  browser and viewport width
* Adaptive websites are built to preset factors
* A combination of both is ideal
* Mobile design on the other hand, is design soley for mobile users
* There are three main components of responsive design
    1. flexible layouts
        * uses a flexible grid that is capable of dynamically sizing to any width
        * percentages or em
    2. media queries
    3. flexible media
## flexible layouts
    * dont use fixed units like pixels or inches
    * there is a formula for identifying the proportions of a flexible layout
        target / context = result
    * takes the target witdth of an element and divides it by the width of its parent element. The result is the relative width of the target element
## media queries
    * provide the ability to specify different styles for individual browser and device circumstances, such as the width of the view port or device orientation
    * it is recommended to use @media rule inside of an existing style sheet
        ```
        HTML
        <link href="styles.css" rel="stylesheet" media="all and (max-width: 1024px)">

        css
        @media all and (max-width: 1024px) {...}
        ```

* types of media include all, tv, screen, print, and braille
    * screen is the default media type
    * logical operators: `and`, `not` , and `only`
#### Floats
* float property has four valid values: left, right, none and inherit
* the clear property is used on an element to make it move past the float