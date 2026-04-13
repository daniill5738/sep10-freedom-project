# Tool Learning Log

## Tool: Bulma


### 3/21

* I learned how to use Bulma columns to organize my layout

  * Bulma uses `columns` and `column` instead of `row` and `col`
  * I tested how columns auto space things out

* Example shown below:

```html
  <div class="columns">
    <div class="column">Text</div>
    <div class="column">Text</div>
  </div>
```
  * Challenge: getting used to div class names

A challenge I had was getting used to the different class names compared to Bootstrap
I learned that Bulma is easier to read but still works similarly

* https://bulma.io/documentation/
* Tried columns, sizes, buttons
* Challenge: different div classes from Bootstrap
* Next: Use this tool for my FP project.

### 3/30

* Bulma has only a css and no built in javascript
* Flexbox for layout
* Easy readable class/div names

* Challenge was to getting used to this type of tool
<p>it is different than bootstrap, what we usally work on and learned in the past couple of monthes.</p>

### 4/12

* While tinkering with bulma I learned that you can change the size of the buttons, as controls have a default font size of $size-normal and it also can come in 3 additional sizes, which can be accessed traveling through 3 additional mixins.

* `@include controls.control-small;`
 with a font size `$size-small`

* `@include controls.control-medium;`
 with a font size `$size-medium`

* `@include controls.control-large;`
 with a font size `$size-large`
 
* This is the html code shown below

```html
<button class="bulma-control-mixin is-small">
  Small
</button>
<button class="bulma-control-mixin">
  Normal
</button>
<button class="bulma-control-mixin is-medium">
  Medium
</button>
<button class="bulma-control-mixin is-large">
  Large
</button>
```
<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
