gibberishjs
===========

Make text on a webpage unreadable gibberish

see http://clanceyp.github.io/gibberish.js 

## usage example

```[js]
(function(el){
    var script = document.createElement('script');
    script.onload = function () {
        if (el) {
            gibberish.go(el);
        }
    };
    script.src = "https://rawgit.com/clanceyp/gibberish.js/master/gibberish.js";
    document.head.appendChild(script)
})( /* optonal element e.g. document.querySelector("body") */ );

```
