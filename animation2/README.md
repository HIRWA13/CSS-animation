# Introduction to Animation with CSS

## CSS animation using the transform property

with the transform property you can move, rotate, scale, and skew elements in 2D and 3D space.

the transform property can be used in two different ways, the first way is to use the transform property as a single property, the second way is to use the transform property as a shorthand property.

### The transform property as a single property

the transform property can be used as a single property, this means that you can use the transform property to move, rotate, scale, and skew elements in 2D and 3D space.

the transform property can be used as a single property in the following way:

```css
    transform: value;
```

the value of the transform property can be one of the following values:

* translate()
* translateX()
* translateY()
* translateZ()
* translate3d()
* rotate()
* rotateX()
* rotateY()
* rotateZ()
* rotate3d()
* scale()
* scaleX()
* scaleY()
* scaleZ()
* scale3d()
* skew()
* skewX()
* skewY()
* matrix()
* matrix3d()


### The transform property as a shorthand property

the transform property can be used as a shorthand property.

the transform property can be used as a shorthand property in the following way:

```css
    transform: translate(50px, 100px) rotate(45deg) scale(2, 2);
```

### transform with translate property

the translate property is used to move elements in 2D and 3D space.

the  translate property can be used in the following way:
    
    ```css
        transform: translate(x, y);
    ```

    the x value is used to move the element horizontally, the y value is used to move the element vertically.

    
example:

    ```css
        transform: translate(50px, 100px);
    ```

translate can be used in 3 different ways: 

* translate(): in this way, an element can be moved both horizontally and vertically.
* translateX(): in this way, an element  is  moved horizontally.
* translateY(): in this way, an element is moved vertically.

```css
    transform: translate(50px, 100px); /*this element will be moved in both horzontal and vertical directions*/
    transform: translateX(50px) /* this element will be moved in an horizontal direction*/
    transform: translateY(50px) /*this element will be moved in a vertical direction*/
```


#### Transitions

CSS transitions allows you to change property values smoothly, over a given duration.
CSS transitions allows us to animate changes to a CSS property.

or in other words, they help us to change the flow of the css property value. for example, if we want to change the color of a button when the user hovers over it, we can use the transition property to change the color of the button smoothly.

example: 

    ```css
        button{
            background-color: red;
            transition: background-color 1s;
        }
    
        button:hover{
            background-color: blue;
        }
    ```
in the above example, the background color of the button will change from red to blue smoothly when the user hovers over the button.

#### The transition timing function:

the transition timing function is used to specify the speed of the transition effect.
we use the transition timing function when we want to change the feel of our animation.

we have 4 different transition timing functions:

* ease: this is the default value, the animation starts slowly, then it speeds up in the middle, then it slows down again at the end.
* linear: the animation has the same speed from start to end.
* ease-in: the animation starts slowly, then it speeds up towards the end.
* ease-out: the animation starts fast, then it slows down towards the end.


example:
    
        ```css
            button{
                background-color: red;
                transition: background-color 1s ease-in;
            }
        
            button:hover{
                background-color: blue;
            }
        ```

#### transition delay:

the transition delay property specifies when the transition effect will start in seconds or milliseconds.

### transform with scale property

the scale property is used to scale elements in 2D and 3D space.
by scale I mean that we can use the scale property to make the element smaller or bigger depending on the value we gave the scale property.

the scale property can be used in the following way:

    ```css
        transform: scale(x, y);
    ```

    the x value is used to scale the element horizontally, the y value is used to scale the element vertically.

example:

    ```css
        transform: scale(2, 2);
    ```

scale can be used in 3 different ways:

* scale(): in this way, an element can be scaled both horizontally and vertically.
* scaleX(): in this way, an element is scaled horizontally.
* scaleY(): in this way, an element is scaled vertically.

```css
    transform: scale(2) /*this will increase the size of an element on both x-axis and y-axis*/
    transform: scaleY(2) /*this will increase the size of an element on  y-axis*/
    transform: scaleX(2) /*this will increase the size of an element on  x-axis*/
```

### transform with rotate property:

the rotate property is used to rotate elements in 2D and 3D space.

the rotate property can be used in the following way:
    
        ```css
            transform: rotate(angle);
        ```

        we use the angle value to rotate the element at certain amout of degrees depending on the initial value the element had.

example:

        ```css
            transform: rotate(45deg);
        ```

        the above element will rotate 45 degrees clockwise.

        ```css
            transform: rotate(-45deg);
        ```

        the above element will rotate 45 degrees anti-clockwise

### transform with skew property:

the skew property is used to skew elements in either horizontal or vertical directions.

the skew property can be used in the following way:

        ```css
            transform: skew(x-angle, y-angle);
        ```

        the x-angle value is used to skew the element horizontally, the y-angle value is used to skew the element vertically.

example:

        ```css
            transform: skew(45deg, 45deg);
        ```
        the above element will skew 45 degrees horizontally and 45 degrees vertically.

skew can be used in 3 different ways:

* skew(): in this way, an element can be skewed both horizontally and vertically.
* skewX(): in this way, an element is skewed horizontally.
* skewY(): in this way, an element is skewed vertically.

```css
    transform: skew(45deg, 45deg) /*this will skew an element both horizontally and vertically*/
    transform: skewX(45deg) /*this will skew an element horizontally*/
    transform: skewY(45deg) /*this will skew an element vertically*/
```



## Author

* [Junior Hirwa](https://github.com/HIRWA13)