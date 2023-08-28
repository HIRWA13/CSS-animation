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