# remark.search

A quick hack to add search capabilities to [remark](https://github.com/gnab/remark) slideshows. 

**Dependencies**: 
  * [mark.js](https://markjs.io/)

**Usage**: 

~~~html
<link rel="stylesheet" href="remark.search.css">
<script src="remark.search.js" type="text/javascript"></script>
~~~

~~~javascript
window.addEventListener('load', function() {
  RemarkSearch.create({'position': 'top-right', 'caseSensitive' : true});
});
~~~

**Options**:
  * **position**: top-left, top-right, bottom-left or bottom-right.
  * **caseSensitive**: true or false.

**Screenshot**:

<p align="center">
<img src="https://cdn.pbrd.co/images/GQWEGvX.png">
</p>
