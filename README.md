Here's a simple example of your cake website task. I've detailed whts going on in each css file below


## Layout

Here I've taken the bare bones of the bootstrap grid system to show you how it works fundamentally. 

The basic concept is that there are rows which contain columns. Each row can have a maximum of 12 individual columns before it wraps to another line. The col class translates to a percentage width.

i.e you could have four .col-3 siblings within a row class element as this would add up to twelve.

In terms of how the gridview works with this:
 
 #### Row Class
The row class sets display to 'flex' so the element acts as a flex container for its children.
 
 #### Col Class
The col class uses the 'flex-status' property. This allows you to set the width of the child flex element.
 
 
## Spacing

Padding and margin is handled in this file. the 'm' classnames signify margin classes and 'p' classes padding.
More specfic margin and padding styles use one letter in the class name to specific the direction you want the padding or margin to be applied: 
 
i.e 'ml' is margin left.


## Colour

There's three classes here for the three main colours. When setting up a colour scheme like this use generic classes so you can easily change colours in the future without having to edit lots of css classes.

i.e everything with the css class of 'dark-2-bg' shares the same background colour you specify in that class. If you change this background value, it will change for every element with that class name.
