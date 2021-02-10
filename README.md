# Aiwizo Styles

Stylesheets and resources for Aiwizo application design.

## Usage

### React

```
npm install @aiwizo/application-styles
```

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

### CDN

Include the stylesheet with [jsDelivr](https://www.jsdelivr.com/)

```
https://cdn.jsdelivr.net/gh/aiwizo/application-styles@<commit-hash>/<file-name>
```

or combine several

```
https://cdn.jsdelivr.net/combine/gh/aiwizo/application-styles@<commit-hash>/<file-name>,gh/aiwizo/application-styles@<commit-hash>/<file-name-2>
```

**EXAMPLES**:

```
https://cdn.jsdelivr.net/gh/aiwizo/application-styles@latest/layout.css
```

```
https://cdn.jsdelivr.net/gh/aiwizo/application-styles@5d0006cca02f61990cfda86f4ef4d3a21efc0d84/layout.css
```

```
https://cdn.jsdelivr.net/combine/gh/aiwizo/application-styles@latest/reset.css,gh/aiwizo/application-styles@latest/fonts.css,gh/aiwizo/application-styles@latest/colors.css,gh/aiwizo/application-styles@latest/animations.css
```

```html
<link
  href="https://cdn.jsdelivr.net/gh/aiwizo/application-styles@latest/layout.css"
  rel="stylesheet"
/>
```
