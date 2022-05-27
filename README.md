# JQuery-Routes

### Add route for a page
```
$.router.add('/:item', function(data) {
  $('#container').load('/news.html');
});
```
```
function goNews() {
  $.router.go('/news', 'Title');
}
```

### HTML button
```
<div id="container">
  <button onclick="goNews();">News</button>
</div>
```
