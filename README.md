# CSS Animation.

in this repository includes some of the lessons and the codes regarding CSS animation and how to use them.

## What is CSS Animation?

CSS animation is a method of animating certain HTML elements without having to use javascript or flash. It is a very simple and easy way to add animations to your website.

## How to use CSS Animation?

CSS animation is very easy to use. All you have to do is to add the animation property to the element you want to animate. The animation property includes the animation-name, animation-duration, animation-timing-function, animation-delay, animation-iteration-count, animation-direction, animation-fill-mode, and animation-play-state.

## Example

```css
div {
    width: 100px;
    height: 100px;
    background-color: red;
    animation-name: div-animate;
    animation-duration: 4s;
}

@keyframes div-animate {
    0% {
        background-color: red;
        transform: translateX(0px);
    }
    50% {
        background-color: blue;
        transform: translateX(20px);
    }
    100% {
        background-color: red;
        transform: translateX(60px)
    }
}
```

## What is the difference between animation and transition?

The difference between animation and transition is that animation is a change from one set of CSS styles to another. Transition is a change from one CSS style to another.