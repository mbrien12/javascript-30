
# My JS 30 - Key takeaways

## #1 - Drum Kit
* The 'transitionend' EventListener
* The 'data-key' attribute

## # 2 - JS & CSS clock
* Cubic bezier transition
* `Transform: 'rotate'`

## # 3 - CSS variables
* You can create variables! Not using SCSS/SASS 
* Use ':root' e.g.
```
 :root {
      --base: #ffc600;
      --spacing: 10px;
      --blur: 10px;
    }

    img {
    padding: var(--spacing);
    background: var(--base);
    filter: blur(var(--blur));
    }

```
## # 4 - Array cardio 1
* `.filter()` 
* `.map()` - Provide new array based on conditions set
* `.sort()`
* `.reduce()` - Reduces to single value e.g. they are totalled up

## # 5 - Flex panel gallery
* Good practice on toggling classes

## #6 - Type ahead
* Using REGEX in JS
* Reading and parsing JSON from external source with `.fetch()`
* Using `.replace()` to replace HTML with new classes