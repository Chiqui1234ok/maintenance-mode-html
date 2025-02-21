# Maintenance mode HTML

A free template with a card containing:
- A title.
- Two paragraphs.
- A box with a recommendation.
- An slim footer.

See a live [demo](https://chiqui1234ok.github.io/maintenance-mode-html/).

## Night Mode / Dark Mode

In **./assets/css/main.css**, line 100, you will find the color change for dark mode:

```css
@media (prefers-color-scheme: dark) {
    :root {
        --white: #3c3a23;
        --white-alt: #4e4b25;
        --black: #f3f3f3;
        --black-alt: #fff;
    }
}
```