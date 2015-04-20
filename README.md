simple-overlay
==============
Simple overlay is a minimal script (plus styles) to create an accessible overlay.
The only implemented control is closing the overlay by pressing `Esc` on the
keyboard.

License
-------
See the [LICENSE](LICENSE) file.

Usage
-----
The script creates a global `Overlay` constructor with the following interface:
 - `isShowing`: Attribute indicating, whether the overlay is currently visible
 - `show()`: method to display the overlay
 - `hide()`: method to hide the overlay
 - `show` Event: fired on the overlay whenever it is shown
 - `hide` Event: fired on the overlay whenever it is hidden

Example
-------
See the [index.html](index.html) for a practical example.
