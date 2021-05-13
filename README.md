# Anchor-JS

*By [Adrii](https://github.com/AdrianVillamayor)*

A JavaScript utility for adding anchor links to page content.

## Demo
Try it 

[![Codepen](https://user-images.githubusercontent.com/29653964/116972608-8f6bca80-acbb-11eb-98c1-8a3b19705de1.png)](https://codepen.io/adrianvillamayor/pen/oNBqoxp)
## Installation

### CDN

```js
<script src="https://cdn.jsdelivr.net/gh/AdrianVillamayor/Anchor-JS@main/src/anchor.min.js"></script>
```

### Manual
```js
<script src="/js/plugins/anchor.js"></script>
```

## Usage

```javascript

$('.anchor[data-anchor]').on("click", function(e) {
    e.preventDefault();

    let target = $(this).attr("data-anchor");     

    scrollToAnchor(target);
})

```

# Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

# License
[MIT](https://github.com/AdrianVillamayor/Anchor.js/blob/master/LICENSE)

### Thanks for your help! 🎉
