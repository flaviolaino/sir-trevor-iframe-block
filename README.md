SirTrevor JS iframe block
=======================

## Setup
Start by including the js file on your page after SirTrevorJs:

```html   
<script src="/path/to/sir-trevor-iframe.js"></script>
```

Then Add "Iframe" to the list of block types:

```javascript
var editor = new SirTrevor.Editor({
    el: document.querySelector('.js-st-instance'),
    defaultType: 'Text',
    blockTypes: ['Text', 'Image', 'Video', 'Iframe'],
    iconUrl: 'images/sir-trevor-icons.svg'
});
```

Now you should have the iframe embed block enabled and available to use.