> [!IMPORTANT]
> This repository is currently under active development


# Ruby Red Framework
A minimalist, drop-in CSS "framework" that makes HTML look professional without a single class.

`classless.css` provides a clean, modern aesthetic for web projects by styling semantic HTML tags directly. It’s perfect for personal blogs, documentation, rapid prototyping, and "small web projects" where you want to focus on content, not CSS selectors.

## Key Features
- No Classes Required: Just write standard HTML and it looks great instantly.
- Lightweight: Tiny footprint for fast load times.
- Responsive by Default: Looks great on mobile, tablet, and desktop.
- Dark Mode Support: Automatically switches themes based on system preferences.
- Typography Focused: Designed for readability with a clean, system-font stack.

## Why another one?
While there are many excellent classless stylesheets available, this personal project isn't meant to compete. Instead, it serves four specific goals:
- Creating a "unique" visual identity.
- Keeping pace with the latest language developments and features.
- Staying truly classless by relying strictly on native HTML elements.
- Ensuring full A11y compliance for an inclusive user experience.

## Getting Started

### Manual Installation
1. Download the classless.css file from this repository and include it in the project folder. 
2. Then add it to the index.html:

```
<link rel="stylesheet" href="path/to/classless.css">
```

## Usage
Simply write semantic HTML.

## Customization
You can easily override the default colors and fonts by defining CSS variables in your own stylesheet:
```
:root {
  --bg: #ffffff;
  --bg-secondary: #f8f9fa;
  --font-size-base: clamp(1.125rem, 0.25vw + 1rem, 1.25rem);
}
```

In addition, a custom CSS file can be used in conjunction with the classless CSS file, where the classless CSS supplies a "sensible default" or base layer, while the custom file handles branding and specific design needs.

## Roadmap
There will be updates from time to time, since it is being used for personal projects.
