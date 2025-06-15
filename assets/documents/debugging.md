# Bug 1

The problem I am having is when I increase the size of parent2 (form, button and p tags) it pushes down the banner containing the logo and brand name.

My first thought was to try and make the background image in parent 1 act as the background-color of the div this way the banner will sit inside without the use of the position property.

# Solution

My first thought was correct by removing the background image from the html and adding the background image property to the parent 1 div are banner now sits inside without the position property which has solved the problem.
the CSS used can be seen below.

```CSS
#first-parent1 {
    display:flex;
    justify-content: center;
    background-image: 
        url("./images/background.png");
    background-repeat: no-repeat;
    background-size: 100% 100%;
    height: 100vh;
    width: 33vw;
}
```
