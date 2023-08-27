# simpledev.css

The goal of simpledev.css is to create a mostly classless CSS framework. We are starting off with working on a handful of components and will add the classless code later.

## Getting Started

These components were developed using modern-normalize.css. It's recommended that you include modern-normalize.css in your project if you're going to use this framework.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/modern-normalize@2.0.0/modern-normalize.min.css">
```

## Contributing

Use the file `_simpledev.css` when you're testing out new code. This file uses import statements.

```html
<link rel="stylesheet" href="css/_simpledev.css">
```

When you're done testing out your code and you're ready to submit your work, use the following command to combine the individual CSS files into one final CSS file.

```
cat buttons.css container.css navbar.css > simpledev.css
```
