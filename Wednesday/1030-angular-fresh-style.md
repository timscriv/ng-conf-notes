# Justin Schwartzenberger - Angular 2's Fresh Approach to Style

- Front end developers are design implementers
- Why the CSS Shim
    - View Encapsulation Modes for Components
        - native (uses shadow DOM, web components)
        - none (no shadow DOM, but will output the style just like we wrote it)
        - default) emulated (adds specific tags to emulate shadow DOM with unique attribute names)
- **What are the negatives about putting the style tags up in the head for each component?**
- Shadow DOM Style Hosting
    - :host
        - targets the custom root element of the directive
    - :host-context
        - targets higher in the DOM tree than the root element(ancestors)
    

