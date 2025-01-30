## HTML Quotation

- Blockquote : <blockquote>
- Quotations : <q>
- Abbreviation : <abbr>
- Address : <address>
- Cite : <cite>
- Bi-Directional Override : <bdo>

## HTML comments

- HTML Comments are not displayed in the browser, but it helps to write hints or comment in the source code.

## HTML Links

Links allow users to click their way from page to page.

### HTML Links - Hyperlinks

When we click on a link and jump to another document.

When we move the mouse over a link, then mouse arrow will turn into a little hand.

```
<a href="url">Link Text</a>
```

States of a link:

- Unvisited : Underline and blue
- Visited : Purple
- Active : Red

**Target Attribute**

By default, the linked page will be displayed in the current browser window. To change this, we must have to specify the target attribute for the link.

target:
    - _self : Default, Opens the document in the same window
    - _blank : It opens the document in the new tab
    - _parent : It opens the document in the parent frame
    - _top : It opens the document  in the full body of the window