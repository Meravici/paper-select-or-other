[![Build Status](https://travis-ci.org/Meravici/paper-select-or-other.svg?branch=master)](https://travis-ci.org/Meravici/paper-select-or-other)
# \<paper-select-or-other\>

`paper-select-or-other` is built upon `paper-dropdown-menu` and gives you the ability to have a custom input field alongside with predefined list of items

## Installation

Install using bower: `bower install Meravici\paper-select-or-other`

## Usage

<!---
```
<custom-element-demo>
  <template is="dom-bind" id="Demo">
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-select-or-other.html">
    <next-code-block></next-code-block>
  </template>
  <script>
    Demo.dinosaurs = [
        'allosaurus',
        'brontosaurus',
        'carcharodontosaurus',
        'diplodocus'
    ];
  </script>
</custom-element-demo>
```
-->

```html
<paper-select-or-other label="Label"
                       items="[[dinosaurs]]">
</paper-select-or-other>
```

Detailed docs with demo can be found [here](https://meravici.github.io/paper-select-or-other/components/paper-select-or-other/)

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
