# remark.search

A quick hack to add search capabilities to [remark](https://github.com/gnab/remark) slideshows. 

**Dependencies**: 
  * [mark.js](https://markjs.io/)
  * [Font Awesome](http://fontawesome.io/)

**Demonstration**: https://web.fe.up.pt/~arestivo/remark.search/ (try pressing Ctrl+F, searching for slide and then F3)

**Usage**: 

```html
<link rel="stylesheet" href="remark.search.css">
<script src="remark.search.js" type="text/javascript"></script>
```

```javascript
window.addEventListener('load', function() {
  RemarkSearch.create({'position': 'top-right', 'caseSensitive' : false, 'showIcon': false}, 'autoSearch': true});
});
```

**Options**:
  * **position**: top-left, top-right, bottom-left or bottom-right (position of search box).
  * **caseSensitive**: true or false.
  * **showIcon**: true or false (show icon to open/close search).
  * **autoSearch**: true or false (search on each keystroke).

**Keyboard Shortcuts**:

  * **Ctrl+F**: Open search bar (or just click on icon if visible) 
  * **Esc**: Close search bar (or just click on icon)
  * **Enter**: Search
  * **F3**: Next match or search
  * **Shift+F3**: previous match or search

**Colors**:

You can change the visual aspect of found matches by altering the following CSS rules:

```css
span.match.current-match {
  background-color: #26f944;
}

span.match {
  padding: 1px;
  background-color: #26dcf9;
  color: black;
}
```

**Screenshot**:

<p align="center">
<img src="https://cdn.pbrd.co/images/GQWEGvX.png">
</p>
