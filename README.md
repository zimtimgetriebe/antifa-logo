# Antifa logo
Using Font Awesome to create the Antifa logo. 

![scrrrn](https://cloud.githubusercontent.com/assets/12021646/11008472/0aa3269e-84d1-11e5-99c9-5741d5c2f3e1.png)

### [Demo](http://codepen.io/zimtimgetriebe/pen/zvJjJV/)

[Font Awesome](https://fortawesome.github.io/Font-Awesome/) is a nice webservice offering it's popular icon font to use. 
By using the [stacking technique](http://fortawesome.github.io/Font-Awesome/examples/#stacked) we are able to create this. 


### How to use this

You can use `<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">` to include a minified and _<abbr title="Content Delivery Network">cdn</abbr>'ed_ version of Font Awesome in your document. From there you simply add the content of [style.css](https://github.com/zimtimgetriebe/antifa-logo/blob/master/style.css) or include it's raw from this github repository: `<link rel="stylesheet" href="https://raw.githubusercontent.com/zimtimgetriebe/antifa-logo/master/style.css">`.

Insert this inside `<body>` where you want it to be:
```html
<span class="fa-stack fa-lg fa-5x">
  <i class="fa fa-flag fa-stack-1x fa-flip-horizontal flag-back red"></i>
  <i class="fa fa-flag fa-stack-1x fa-flip-horizontal flag-front black"></i>
  <i class="fa fa-circle-o fa-stack-2x black"></i>
</span>
```

### Tweaking
You can modify it very simple with the already existing font-awesome classes e.g. `fa-1x` &mdash; `fa-5x`. Some predefined colors as classes are `red`, `black`, `pink`, `gray`, and `darkgray`. 

