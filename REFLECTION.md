# Code Reflection

## 1. Can I explain what my code does?

For this assignment, I added a CSS file to my existing HTML resume. I already had a solid resume structure when I finished the 1st assignment. All that's left is to add my own personalized styling! CSS achieves that by defining a set of rules to style my sections and elements.

When doing this assignment, I also learned a lot of cool CSS features and web design tips that are outside of this module's discussion.

- Using CSS custom properties
- Using a type and spacing system
- The `clamp()` function for responsive, scalable font and spacing sizes.
- Container Queries
- `transition` property
- New relative units like `ch`, `fr` (in grids), and `vh`
- The `:root` selector.

## 2. What was my coding process?

Before I started coding my styles, I first had to find a fitting theme and layout. I filled out the `DESIGN_GUIDELINES.md` first and made some rough wireframe sketches of my layout on paper.

The following is a quick, high-level overview of my coding process for this assignment:

1. Applied a partial CSS reset (set my margin and padding to 0).
2. Looked for a _type_ and _spacing_ system online.
   - That way, my sizes stay consistent and I don't have to think about it when setting them.
   - This is the step where I also learned about custom properties in CSS.
3. Defined my color scheme with custom properties for reuse.
4. Implement a Grid layout for my overall structure.
5. Styled the `<main>` resume content first.
6. Styled the `<aside>` (sidebar)
7. Styled the `<header>` and `<footer>`
8. Implement media queries to my sections

I learned most of the cool features (listed in the prev. question) when I was styling the content of my resume.

## 3. What challenges did I have?

**Responsiveness**

I had difficulty implementing responsiveness to my resume. After finishing most of styles in a desktop view, scaling down my content to a smaller screen was very tricky, because most of my styles are tailored to wider, bigger screens. Every time I had to add a media query breakpoint (scale down), I had to apply a new set of CSS rules just to make them look right. In addition, media queries couldn't resolve all of my responsiveness issues, so I started exploring container queries - a relatively new way to add responsiveness.

**Growing `CSS` file**

Another challenge I encountered was managing my CSS file as the project grew. As I added more and more styles, the stylesheet became cluttered, making it difficult to track which styles were affecting specific parts of the page

**Figuring out correct layouts**

I found that figuring out and testing the correct layout with either CSS Grid or Flexbox was very time-consuming. I spent a lot of time tweaking properties and values to get things aligned just right.

## 4. What would I do differently now?

**Start from mobile first**

Looking back, I realized it would have been more efficient to adopt a **mobile-first approach** from the beginning, building the layout for mobile screens first and then progressively scaling up to larger, desktop screens.

Working my way down to a smaller screen with media queries was difficult. It feels as if I'm creating a new layout for each breakpoints. In contrast, I think scaling my layout up would just be matter of filling up the empty space by making some small tweaks in my existing layout.

**Use prototyping tools like Figma**

In addition, it would have been much more efficient to use a prototyping tool like Figma to visualize and plan the layout before I started coding it in. My rough wireframe sketch did help and establish the foundational layout of my resume, but when it comes to experimenting and testing new layouts it was time-consuming. I think it would be better to experiment in visual prototyping tools like Figma.

**Break my `CSS` file?**

Maybe I should break apart my `css` file into two parts: a base file and style file. The base will contain rules for CSS reset and custom properties for my color scheme, type, and spacing systems. The style file will then contain styling rules for my webpage. I noticed that the reset, color, and spacing rules took up a huge portion of my css file making it harder for me to navigate specific webpage rules.
