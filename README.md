# Task 4 – Mobile Responsive Website

## What was done

This task started with a desktop-style website called **InovaTech**.

The website contains:
- A navigation bar
- A hero section
- Buttons
- A services section with three cards
- A footer

### Desktop design

The website was first designed mainly for large screens. It uses a horizontal layout for the navigation, hero section, and service cards.

### Mobile responsiveness

CSS media queries were then added to make the website work better on smaller screens.

The main responsive changes were:

- The navigation changes from horizontal to vertical.
- The hero section changes from two columns to one column.
- The text and image fit the screen width.
- Large headings are reduced on mobile.
- Buttons become full-width.
- The three service cards stack vertically.
- The hero design becomes smaller.
- Spacing and padding are reduced for smaller screens.
- The footer is adjusted for mobile.

## Media Query Used

The mobile styles are activated when the screen width is **768px or smaller**:

```css
@media (max-width: 768px) {
    /* Mobile styles */
}
```

## Testing

The website can be tested using Chrome DevTools:

1. Open `index.html` in Chrome.
2. Press `Ctrl + Shift + M`.
3. Select a mobile device or set the screen width manually.
4. Resize the screen and check that the layout adapts.

## Files

- `index.html` – Website structure
- `style.css` – Desktop and mobile CSS
- `README.md` – Simple explanation of the project
