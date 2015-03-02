# webstorm-templates
Set of templates for webstorm. To add a template to webstorm just add the snippet in `Live Templates` section in `Settings > Editor`.

IIFE
--------

IIFE (Immediately-Invoked Function Expressions) aka SEAF Self-Executing Anonymous Function, useful technique to prevent global scope pollution.

``` javascript
(function(){
  $END$
}());
```
