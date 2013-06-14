readmore-readless
=================

A jquery plugin for Read more and Read less functionality

 Consider an HTML div like following: 
```html
<div id="readMoreReadLess">
    <ul class="item">
        <li>Item 1</li>
        <li class="details">Details of Item 1</li>
    </ul>

    <ul class="item">
        <li>Item 2</li>
        <li class="details">Details of Item 2</li>
    </ul>

    <ul class="item">
        <li>Item 3</li>
        <li class="details">Details of Item 3</li>
    </ul>
</div>
```


We can achieve the Read more and Read less functionality by simple code.

Usage 1: Use the plugin in default mode. There will be two items in the summary and on clicking the Read more link, all items would be displayed.
```javascript          
$("#readMoreReadLess").readMoreReadLess();
```

Usage 2: Setting the items present in the summary as 1. Only one item would appear in the summary.
Use the plugin with items in summary set to 1
```javascript
$("#readMoreReadLess").readMoreReadLess({
      itemInSummary: 1
});
```

Usage 3: Customising the Read More links with user defined text and css class.
```javascript
$("#readMoreReadLess").readMoreReadLess({
        readMoreText: 'Show more items ...',
        readLessText: 'Show fewer items ...',
        readMoreClass:'button',
        readLessClass:'button'
});
```
```options``` is an optional javascript object with parameters explained below.

Options
-------

- **itemClass**
A class name which is present on each item.
*default: 'item'*

- **itemInSummary**
The number of items that should appear in the summary view.
*default: 2*

- **readMoreClass**
A class name which would be applied to Read More link.
*default: 'read-more'*

- **readLessClass**
A class name which would be applied to Read less link.
*default: 'read-less'*

- **readMoreText**
The text for the link representing "Read more"
*default: 'Read more >> '*

- **readLessText**
The text for the link representing "Read less"
*default: 'Read less << '*

- - -

Thanks
- - - -

I would like to thanks Sascha Plaum for upgrading the plugin to support newer version of jquery 1.9.1

This software is made available under the open source MIT License. &copy; 2013 
            
