---
layout: post
title: React Inline-Editor Example

---

I wrote a little React.js inline-editor example and as far as I can tell this is the easiest spot to show an example:

Code on Github: [Here](https://github.com/timtyrrell/react-inline-edit/)

<div id="inline-example"></div>

<script src="https://code.jquery.com/jquery-2.1.3.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/react/0.13.3/react.js"></script>
<script src="https://rawgit.com/timtyrrell/react-inline-edit/master/build.js"></script>
<script>
  document.addEventListener('DOMContentLoaded', function () {
    var rootElement = React.createFactory(InlineContainer)();
    React.render(rootElement, document.getElementById('inline-example'));
  });
</script>
