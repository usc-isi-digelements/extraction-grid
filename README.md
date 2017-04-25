# extraction-grid

A Polymer Element showing a grid of extractions.

### Example
```js
extractions = [{
  name: 'Favorite Projects',
  data: [{
    confidence: 'high',
    highlight: true,
    icon: 'search',
    link: 'https://github.com/DigElements',
    styleClass: 'extraction',
    text: 'DigElements'
  }]
}];
```

```html
<extraction-grid
  extractions="[[extractions]]">
</extraction-grid>
```

### Styling

`<extraction-grid>` provides the following custom properties and mixins for styling:

Custom property                            | Description                                 | Default
-------------------------------------------|---------------------------------------------|-----------------------
`--extraction-grid-high-confidence-color`  | The color of the high confidence icon.      | --paper-blue-600
`--extraction-grid-highlighted-text-color` | The color of the highlighted text.          | yellow
`--extraction-grid-hover-color`            | The color of the extraction label on hover. | --secondary-text-color
`--extraction-grid-label-color`            | The color of the extraction label.          | --primary-text-color
`--extraction-grid-label-mixin`            | Mixin applied to the extraction label.      | {}
`--extraction-grid-low-confidence-color`   | The color of the low confidence icon.       | --paper-orange-600
`--extraction-grid-title-color`            | The color of the extraction title.          | --secondary-text-color

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

