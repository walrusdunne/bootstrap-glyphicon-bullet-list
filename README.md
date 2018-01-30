# Bootstrap Glyphicon Bullet List
A CSS stylesheet that allows any Glyphicon included with Bootstrap 3.3.7 to be used as a &lt;ul> bullet point. Should be used with Bootstrap 3.3.7.

# Usage
Apply the `.glyphicon-bullet-list` class to your `<ul>` element with whichever icon from the Bootstrap Glyphicon set prefixed with `list-`. Eg. `<ul class="glyphicon-bullet-list list-chevron-right">`. This will apply the icon to all `<li>`'s in the list.

If you would prefer to assign each bullet individually, just apply the `list-` classes to the `<li>` elements instead of the `<ul>`. Eg.
```
<ul class="glyphicon-bullet-list">
 <li class="list-chevron-right">This is</li>
 <li class="list-asterix">a test.</li>
</ul>
```

You can also override an icon on an individual `<li>` where the icon has been set on the `<ul>` element, in essence providing a default but allowing an override. Eg.
```
<ul class="gylphicon-bullet-list list-chevron-right">
 <li>This will have a chevron-right</li>
 <li>So will this</li>
 <li class="list-asterix">This will have an asterix</li>
</ul>
```
