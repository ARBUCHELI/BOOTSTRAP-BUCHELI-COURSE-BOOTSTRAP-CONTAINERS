# BOOTSTRAP-BUCHELI-COURSE-BOOTSTRAP-CONTAINERS

Bootstrap uses a grid system based on CSS Flexbox which organizes content in rows or columns. As seen in the previous exercise, Bootstrap also uses rows and columns and in this exercise we’ll learn about the essential Bootstrap container. Using the Bootstrap grid also allows for responsive design, in other words, a website’s layout can change based on the user’s screen size. Read more about grid at Bootstrap’s grid documentation.

Bootstrap uses classes to apply CSS rulesets — these rulesets dictate the layout and styling of the element. To create a container, necessary for Bootstrap’s grid, we assign a class of "container" to a <div> like so:

```
<div class="container"></div>
```

The <div> from the example above becomes a Bootstrap container which has a width relative to a user’s screen size, becomes horizontally centered, and has a left and right margin.

If we wanted the container to take up the entire width of the screen we can assign a class of "container-fluid":

```
<div class="container-fluid"></div>
```

Knowing how to use documentation is important. We can always check what classes to add using Bootstrap’s grid documentation.

Note: the Bootstrap site uses CSS notation for classes, which entails having a . before a class name like .example-class-name.
