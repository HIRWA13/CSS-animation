# @Keyframes animations

in CSS, we can use both animation and @keyframes rule to create better and smooth animations. 

## @Keyframes animations

keyframes are used to create animations. The animation is created by gradually changing from one set of CSS styles to another. During the animation, you can change the set of CSS styles many times. Specify when the style change will happen in percent, or with the keywords "from" and "to", which is the same as 0% and 100%. 0% is the beginning of the animation, 100% is when the animation is complete.

```css
@keyframes mymove {
  from {top: 0px;}
  to {top: 200px;}
}
```

so, we can use the above animation on other elements like this:
    
```css
div {
    animation: mymove 5s infinite;
}   
 ```

```css
@keyframes anotherMove {
    0%   {background-color: red;}
    25%  {background-color: yellow;}
    50%  {background-color: blue;}
    100% {background-color: green;}
}
```

then we can use the *anotherMove* keyframe on other elements like this:
    
```css
div {
animation: anotherMove 5s infinite;
}
```

so in the above example, the background color of the div will change from red to yellow to blue to green and then again red and so on.

## Animation direction: 

the animation direction property specifies whether an animation should be played in a normal, forwards, backwards or in alternate cycles.

1. normal: the animation is played as normal (forwards). This is default
2. reverse: the animation is played in a reversed direction (backwards)
3. alternate: the animation is played forwards first, then backwards

```css
/* example: */
div {
    animation-direction: reverse;
}
```