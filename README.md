# Aiwizo Styles

Stylesheets and resources for Aiwizo application design.

## Installation

```
npm install @aiwizo/application-styles
```

## Basic Usage

### React

```jsx
import "@aiwizo/application-styles";

const SomeComponent = () => (
  <div
    style={{
      backgroundColor: "var(--aiwizo-application-blue)",
    }}
  />
);
```

## CSS Variables

- [colors](./src/colors.css) - application color scheme
- [layout](./src/layout.css) - spacing, border radius etc.
- [fonts](./src/fonts/fonts.css) - font families, font sizes
