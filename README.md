#  ARIA TECHNIQUES
## Internet IS for everyone – but it won’t be unless WE make it so.—Vint Cerf
### The purpose of this technique is to provide a label for objects that can be read by assistive technology. The aria-label attribute provides the text label for an object, such as a button. When a screen reader encounters the object, the aria-label text is read so that the user will know what it is.
### Use screen readers such as JAWS AND NVDA
### Provide the user a good way to navigate and interact with your site. Make your HTML semantic. Semantics is about using the correct element in HTML. There are approximately 110 elements in HTML 5.

### Two of them have no meaning – <div> and <span>. They tell us nothing about the content. They have no built in accessibility features, so we should always check to see if any other elements are better suited. Example of semantic elements: <form>, <table> and <article>. They clearly define the content.

### When authors use collapsible content, for example, to hide navigation menus or lists of content, the triggering link or button should indicate to screen reader users whether the collapsable content below is in the expanded or in the collapsed state. The aria-expanded attribute is used for this purpose