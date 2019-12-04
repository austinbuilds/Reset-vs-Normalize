# Reset-vs-Normalize
A comparison of Eric Meyer's Reset and Nicolas Gallagher's Normalize. View [here](https://austinbuilds.github.io/Reset-vs-Normalize/).

# Eric Meyer's Reset
Visit the original post [here](https://meyerweb.com/eric/tools/css/reset/).

>"The goal of a reset stylesheet is to reduce browser inconsistencies in things like default line heights, margins and font sizes of headings, and so on. The general reasoning behind this was discussed in a May 2007 post, if you're interested. Reset styles quite often appear in CSS frameworks, and the original "meyerweb reset" found its way into Blueprint, among others.
>The reset styles given here are intentionally very generic. There isn't any default color or background set for the body element, for example. I don't particularly recommend that you just use this in its unaltered state in your own projects. It should be tweaked, edited, extended, and otherwise tuned to match your specific reset baseline. Fill in your preferred colors for the page, links, and so on.
>In other words, this is a starting point, not a self-contained black box of no-touchiness.
>If you want to use my reset styles, then feel free! It's all explicitly in the public domain (I have to formally say that or else people ask me about licensing). You can grab a copy of the file to use and tweak as fits you best. If you're more of the copy-and-paste type, or just want an in-page preview of what you'll be getting, here it is."

# Nicolas Gallagher's Normalize
Visit the original post [here](https://github.com/necolas/normalize.css/).

>"Normalize.css is an alternative to CSS resets. The project is the product of 100’s of hours of extensive research by Nicolas and Jon Neal on the differences between default browser styles.
>The aims of normalize.css are as follows:
>* Preserve useful browser defaults rather than erasing them.
>* Normalize styles for a wide range of HTML elements.
>* Correct bugs and common browser inconsistencies.
>* Improve usability with subtle improvements.
>* Explain the code using comments and detailed documentation.
>* It supports a wide range of browsers (including mobile browsers) and includes CSS that normalizes HTML5 elements, typography, lists, embedded content, forms, and tables."

# Reset vs Normalize
The following is provided from Nicolas Gallagher [here](https://github.com/necolas/normalize.css/).

>"It’s worth understanding in greater detail how normalize.css differs from traditional CSS resets.
>* Normalize.css preserves useful defaults.
>* Resets impose a homogenous visual style by flattening the default styles for almost all elements. In contrast, normalize.css retains many useful default browser styles. This means that you don’t have to redeclare styles for all the common typographic elements.
>* When an element has different default styles in different browsers, normalize.css aims to make those styles consistent and in line with modern standards when possible.
>* Normalize.css corrects common bugs.
>* It fixes common desktop and mobile browser bugs that are out of scope for resets. This includes display settings for HTML5 elements, correcting font-size for preformatted text, SVG overflow in IE9, and many form-related bugs across browsers and operating systems.
>* Resets often fail to bring browsers to a level starting point with regards to how an element is rendered. This is particularly true of forms – an area where normalize.css can provide some significant assistance.
>* Normalize.css doesn’t clutter your debugging tools. A common irritation when using resets is the large inheritance chain that is displayed in browser CSS debugging tools. This is not such an issue with normalize.css because of the targeted styles and the conservative use of multiple selectors in rulesets.
>* Normalize.css is modular. The project is broken down into relatively independent sections, making it easy for you to see exactly which elements need specific styles. Furthermore, it gives you the potential to remove sections (e.g., the form normalizations) if you know they will never be needed by your website.
>* Normalize.css has extensive documentation. The normalize.css code is based on detailed cross-browser research and methodical testing. The file is heavily documented inline and further expanded upon in the GitHub Wiki. This means that you can find out what each line of code is doing, why it was included, what the differences are between browsers, and more easily run your own tests."

## :man_technologist: Author

* **Austin** - [austinbuilds](https://github.com/austinbuilds)

