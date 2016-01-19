# Code samples

## FED stuff:

 * CSS = scss
 * HML = HTML5
 * Js = meteor, react, angular

Write pragmatic testable code :+1:

### HML = Hypster Markup Language

Keep structure simple use;

```html

<!-- no comments needed -->
<d class="menu">
	<a>
    	Just use d for div and s for span.
    </a>
    <a>
    	That is <s class="strong">all</s>.
    </a>
</d>

```

Instead of;

```html

<!-- no comments needed -->
<menu>
  <ul class="menu">
      <li>
          <a>
              Just use d for div and s for span.
          </a>
      </li>
      <li>
          <a>
              That is <span class="strong">all</span>.
          </a>
      </li>
  </ul>
</menu>

```
### CSS is a deceptively simple language, use but don't abuse the cascade
Use as few variables as possible but, use them everywhere possible.
Use css classes for everything and nest as shallowly as possible.

```css

$color: #f00 !default;
$padding: 10px;

.Main-menu {
  a.link {
  	color: $color;
      &:hover {
      color: lighten($color, 10);
    }
  }
}

```


```javascript
var messg = "annoying!";
console.log(messg);
```

### Other stuff to right click on..

 * [simpl](http://simpl.romack.net) My css framework before there was bootstrap
