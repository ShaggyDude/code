# Code samples

## FED (Front End ~~Developer~~ Dude) stuff:

*Note, I have been doing this way too long.

 * CSS = scss
 * HML = HTML5
 * Js = meteor, react, angular

Write pragmatic testable code :+1:

### HML = Hypster Markup Language

Keep structure simple use;

```html

<!-- no comments needed -->
<d class="Menu">
	<a class="link">
    	Just use d for div and s for span.
    </a>
    <a class="link">
    	That is <s class="strong">all</s>.
    </a>
</d>

```

Instead of;

```html

<!-- no comments needed -->
<menu>
  <ul class="Menu">
      <li>
          <a class="link">
              Just use d for div and s for span.
          </a>
      </li>
      <li>
          <a class="link">
              That is <span class="strong">all</span>.
          </a>
      </li>
  </ul>
</menu>

```
### CSS is a deceptively simple language, use but don't abuse the cascade
Use as few variables as possible but, use them.
Use css classes for everything and nest as shallowly as possible.

```css

$color: #f00 !default;
$padding: 10px;

.Menu {
  a.link {
  	color: $color;
      &:hover {
      color: lighten($color, 10);
    }
  }
}

```
#### CSS naming conventions and library

Use prefix free => [prefixfree](http://leaverou.github.io/prefixfree/)

Use something sensible like this => [semanticUI](http://semantic-ui.com/)

```javascript
var messg = "annoying!";
console.log(messg);
```

### Other stuff to right click on..

 * [simpl](http://simpl.romack.net) => My css framework before there was bootstrap
 * [portfolio](http://romack.net) => My portfolio
 * [portfolio2](http://new.romack.net) => My portfolio in black
