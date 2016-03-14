HTML
========

HTML general best practices

* Use HTML5 Doctype.
* Use proper page encoding.
* Tags and attribute names must be lowercase, except for `<!DOCTYPE html>`.
* Use double quotes for attributes.
* Close all tags. Self-closing tags must be closed with ` />`, including the space.
* Make use of semantical elements. `<div>` and `<span>` are generic tags and must only be used if no other tag fits better.
* Use labels for every form field. Use the `for` attribute to associate labels to an input's id.
* Do not use the size attribute on input fields, use CSS instead.
* Use an HTML comment on the closing tag of large grouping elements to indicate the element you're closing.
* Don't use tables or lists for layout. HTML must be used for content only. Presentation must be handled using CSS.
* Use proper indentation, set the tab size to 2 spaces, soft tabs.
* Partial names begin with underscores.
* WMake sure to provide fallbacks for unsupported HTML5 features.
* Avoid the use of images to replace text.

Semantic use of elements
-------

* Make appropriate use of sectioning elements.
* Every section must have a heading, even if it's not visible.
* `<strong>` and `<em>` must be used for important or highlighted content, not for bold or italic styling.
* Use `<p>` elements for paragraph delimiters instead of `<br>` tags.
* Item lists should always be placed in `<ul>`, `<ol>`, or `<dl>`. Don't use a set of `<div>` or `<p>`.
* Make use of `<thead>`, `<tbody>`, `<tfoot>`, and `<th>` tags when appropriate.
* Avoid using inline CSS or JavaScript inside the HTML code.
* Use `<img>` for elements such as photos, logos, or any other element that should be treated as content or have an important semantic meaning. For backgrounds and decorations use CSS.
