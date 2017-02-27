Table of Contents Generation
============================

Automatically generate a table of contents in Jekyll.

See an [example page](http://tobin.yehle.io/toc-generation/).

Read about [the details](http://tobin.yehle.io/articles/table-of-contents).

To Use
------

Add
- \_includes/toc.html
- js/toc.js
- js/jquery-3.1.1.slim.min.js (optional)

to your site.

Generate a toc for your page with
```
{% include toc.html %}
```

Options
-------

- `tags`: Specify which tags to generate links for. eg: `{% include toc.html tags="H2,H3" %}`
- `ignore`: Ignore any tag matched by a jQuery selector. eg: `{% include toc.html ignore="#sections" %}`
