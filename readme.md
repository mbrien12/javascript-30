
# My JS 30 - Key learnings

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

## # 7 Array cardio 2
* `.some()` - returns true if one of the items in the array meets x condition
* `.every()` - returns true only if all items meet condition
* `.find()` - will return first item that meets this condition
* `.findIndex()` - return index of item that meets condition

## # 8 - HTML5 Canvas
* Drawing in canvas within browser with `.ctx`
* HSL colour values (Hue, Saturation, Lightness)

## # 9 - Dev tool tricks
* See where JS is being executed by right clicking on DOM element in Elements panel > Break on > attribute modifications
* Different console 'log' types e.g. error/warn/info/timing....

## # 10 - Checking multiple checkboxes by holding shift
* Remember to listen out to all elements that could be interacted with!
* Click event will fire even if use keyboard
* Just save event variable as `e`

## # 11 - Custom HTML Video Player
* 