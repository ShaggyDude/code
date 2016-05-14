# Code samples and standards

## User Interface Developer - Designer:

*Note, I have been doing this way too long.

Whatever standards are used they should be enforced before being pushed to production, preferably with every code checkin..

 * CSS = scss
 * HML = HTML5
 * Media = responsive images & videos, webfonts, SVG
 * Js = meteor, react, angular

Write pragmatic testable code :+1:

### H~~T~~ML = Hipster Markup Language

Keep structure as simple as possible;

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

<menu class="Menu">
  <ul>
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

$primary: #f00; $secondary: #f55; $tertuary: #f99;
$padding: 10px; $margin: 10px; $border: 1px solid #000;

.Menu {
  a.link {
  	color: $color;
      &:hover {
      color: lighten($color, 10);
    }
  }
}

```
#### CSS naming conventions and libraries

Use prefix free => [prefixfree](http://leaverou.github.io/prefixfree/)

Use a reset     => [normalize](https://necolas.github.io/normalize.css/)

Use sensible naming conventions => [semanticUI](http://semantic-ui.com/)

Use some sort of CSS library like Bootstrap. At the least the grids, at the most everything. You get responsive out of the box and it is thoroughly tested

#### CSS optimization

Use sass's (or better yet [Stylus](http://stylus-lang.com/)) @extend to mutate css components without bloat


### Javascript/HTML template sytems = jQuery, meteor, angular...

```javascript

	var template = "?";
    
```

### Other code standards to check out..
* [HTML/CSS](http://codeguide.co/) => twitter's guide

### Other stuff to right click on..

 * [simpl](http://simpl.romack.net) => My css framework before there was bootstrap
 * [portfolio](http://romack.net) => My portfolio
 * [portfolio2](http://new.romack.net) => My portfolio in black
 * [portfolio hidden](http://romack.net/minimalist.htm) => evil flash
 

* [Ugly stuff on codepen](http://codepen.io/ShaggyDude/) <=
