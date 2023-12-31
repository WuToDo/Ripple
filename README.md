![rpl](https://github.com/WuToDo/Ripple/assets/75528637/136ddedd-8924-48f6-9759-80020e1aff81)

# Ripple
**Ripple** effect using vanilla javascript.

This package provides you a simple ripple effect, you can either use it on buttons or any other element.
<br/>

## Usage :
First include the script,
Then you can just simply use the class `.ripple` on any element, and you're good to go.
<br/>
You can [Download](https://github.com/WuToDo/Ripple/archive/refs/heads/main.zip) The package from here.

## Properties :
You can use `rpl-color` for Ripple color, It accepts any color type just like any css color property,
And `rpl-opacity` for the opacity.
<br />
<br />
***Note: Opacity is between [ 0.0 - 1 ]***

![image](https://github.com/WuToDo/Ripple/assets/75528637/5acf7a6e-133c-4639-aa3d-8a099371b5be)
<br/>
<br/>
Example:
<br/>
```
<a class="ripple" rpl-color="black" rpl-opacity="0.3" href="#">
  <i class="arrow-up"></i>
  Next
</a>

<!--Example on button-->
<button class="ripple" rpl-color="rgb(0,0,0)" rpl-opacity="0.4">
  This is a button
</button>
```
