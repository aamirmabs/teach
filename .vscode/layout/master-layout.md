---
marp: true
header: "UGM Marp Template Master Layout"
footer: "Footer text here"
paginate: true
theme: ugm
size: 16:9
---

<!-- _class: heading-minimal -->

# UGM Marp Master Template

## A comprehensive guide to all page layouts and content types

---

<!-- _class: ugm-default -->

# Default Layout: Text & Headings

## Using the base UGM theme

This is a standard content slide with the default white background and Ox Blue text. Use this for most of your presentation content.

### Key features:

- Clean, professional appearance
- Excellent readability
- Perfect for academic and corporate settings
- Lexend Deca body text at 120% line height

**Bold text** emphasizes key points, while _italic text_ adds context.

---

<!-- _class: ugm-default -->

# Default Layout: Bullet Points

- First key point with important information
- Second point with supporting detail
- Third point demonstrating hierarchy
  - Nested sub-point with additional context
  - Another sub-point for clarification
- Fourth main point to conclude

Use bullet lists for:

- Breaking down complex ideas
- Listing key takeaways
- Organizing information logically
- Creating visual breathing room

---

<!-- _class: ugm-default -->

# Default Layout: Ordered Lists

1. Start with the foundational concept
2. Build on previous understanding
3. Introduce intermediate complexity
4. Add nuance and exceptions
5. Conclude with integrated knowledge

Numbered lists work best for:

1. Sequential processes or steps
2. Ranked items by importance
3. Instructions or tutorials
4. Progressive learning pathways

---

<!-- _class: ugm-default -->

# Default Layout: Cards & Boxes

<div class="card">
**Card with Electric Blue accent** – Use for highlighting key takeaways, definitions, or important concepts that deserve visual emphasis.
</div>

<div class="card accent-cambridge">
**Card with Cambridge accent** – Perfect for supplementary information, tips, or best practices that support your main narrative.
</div>

<div class="card accent-azul">
**Card with Azul accent** – Great for technical information, code-related content, or specific technical procedures.
</div>

---

<!-- _class: ugm-default -->

# Default Layout: Two-Column Layout

<div class="columns">
<div>

**Left Column**

Use the left side for primary content or key information. This column can contain:

- Main concepts
- Definitions
- Primary arguments
- Main timeline events

</div>
<div>

**Right Column**

The right side works well for:

- Supporting examples
- Contrasting viewpoints
- Visual elements
- Secondary information
- Supplementary data

</div>
</div>

---

<!-- _class: ugm-default -->

# Default Layout: Blockquotes

> "Education is not the filling of a pail, but the lighting of a fire." – William Butler Yeats

Use blockquotes for:

- Notable quotes or citations
- Testimonials
- Key insights from research
- Memorable statements

Blockquotes automatically render with the Cambridge left border and grey text.

---

<!-- _class: ugm-default -->

# Default Layout: Tables

| Feature           | Benefit                      | Implementation        |
| ----------------- | ---------------------------- | --------------------- |
| Fraunces Headings | Bold, distinctive typography | Applied at 600 weight |
| Lexend Deca Body  | High readability             | 120% line height      |
| Color Palette     | Brand consistency            | 9-color system        |
| Responsive Design | Works on all devices         | Flexible padding      |

Tables use:

- Ox Blue headers with white text
- Striped rows for readability
- Electric Blue bottom border
- Hover effect for interactivity

---

<!-- _class: ugm-default -->

# Default Layout: Code & Technical Content

Here's inline code: `python manage.py runserver`

```python
# Python code block example
def create_presentation(theme="ugm"):
    slides = []
    for section in content:
        slides.append(section.render())
    return compile_to_pdf(slides)

result = create_presentation()
```

Code blocks feature:

- Ox Blue background
- Electric Blue syntax highlighting
- Monospace font for clarity
- Automatic overflow handling

---

<!-- _class: ugm-invert -->

# Inverted Layout: High-Contrast Mode

## Dark Ox Blue with bright accents

This inverted layout provides high contrast and visual emphasis. Perfect for:

- **Code-heavy sessions** where highlighting syntax is critical
- **Emphasis slides** that need to stand out
- **Dark room presentations** for better visibility
- **Technical deep-dives** requiring visual hierarchy

Notice how the Electric Blue and Naples yellow pop against the dark background.

---

<!-- _class: ugm-invert -->

# Inverted Layout: Content with Cards

<div class="card">
**Inverted Card** – Cards automatically adapt to the dark background with subtle transparency. This creates visual depth while maintaining readability.
</div>

Key points on inverted slides:

- Use Naples accents for emphasis
- Keep text high-contrast (white/light)
- [Links](#) automatically switch to Naples yellow
- Cards use semi-transparent backgrounds

The inverted style is excellent for creating visual breaks and directing attention.

---

<!-- _class: ugm-invert -->

# Inverted Layout: Lists & Tables

| Technique               | Contrast Ratio | Accessibility |
| ----------------------- | -------------- | ------------- |
| Text on dark background | 15:1           | AAA compliant |
| Naples accents          | 8.2:1          | AA compliant  |
| Electric Blue text      | 9.1:1          | AA compliant  |

Use inverted layouts strategically:

1. Not for every slide – reserve for emphasis
2. Particularly effective for technical content
3. Great for audience engagement and memory
4. Works well at the start/middle/end of sections

---

<!-- _class: ugm-gradient -->

# Gradient Layout: Vibrant & Dynamic

## Electric Blue → Azul → Ox Blue gradient

The gradient layout adds energy and visual interest. It combines:

- **Electric Blue** for innovation and technology
- **Azul** for professionalism and trust
- **Ox Blue** for stability and depth

Use gradient slides for:

- Section introductions
- Major transitions
- Highlighting key concepts
- Creating visual excitement

---

<!-- _class: ugm-gradient -->

# Gradient Layout: Feature Showcase

**Key Feature 1**
Naples accents shine brightly against the gradient, perfect for drawing attention to important information without overwhelming the design.

**Key Feature 2**
The gradient background creates depth while white text remains perfectly readable. This combination works exceptionally well for feature comparisons.

**Key Feature 3**
Use gradient slides sparingly—perhaps one every 4-5 slides—to maintain impact and prevent visual fatigue.

---

<!-- _class: ugm-gradient -->

# Gradient Layout: Data Visualization

| Component       | Usage Frequency  | Recommendation     |
| --------------- | ---------------- | ------------------ |
| Gradient slides | 15–20% of slides | For major sections |
| Inverted slides | 10–15% of slides | For emphasis       |
| Default slides  | 65–75% of slides | Main content       |

Best practices:

- Pair with high-contrast content
- Limit to 1–2 per major section
- Use for memorable takeaways
- Consider audience and venue

---

<!-- _class: heading-minimal -->

# Minimal Section Header

## Clean, professional transition

---

<!-- _class: heading-funky -->

# Funky Section Header

## Bold, playful engagement

---

<!-- _class: heading-formal -->

# Formal Section Header

## Traditional, authoritative presentation

---

<!-- _class: heading-modern -->

# Modern Section Header

## Contemporary, balanced approach

---

<!-- _class: ugm-default -->

# Using Accent Color Classes

<span class="text-ox-blue">Ox Blue text</span> for standard content

<span class="text-electric-blue">Electric Blue text</span> for highlighting technology

<span class="text-azul">Azul text</span> for links and interactive elements

<span class="text-cambridge">Cambridge text</span> for nature/balance concepts

<span class="text-naples">Naples text</span> for warmth and attention

---

<!-- _class: ugm-default -->

# Using Background Color Classes

<div style="background-color: #1d263b; color: white; padding: 1em; margin: 0.5em 0; border-radius: 5px;">
**Ox Blue background** – Use for dark containers with white text
</div>

<div style="background-color: #00dcf9; color: #1d263b; padding: 1em; margin: 0.5em 0; border-radius: 5px;">
**Electric Blue background** – Vibrant container for key information
</div>

<div style="background-color: #106fbd; color: white; padding: 1em; margin: 0.5em 0; border-radius: 5px;">
**Azul background** – Professional container for important data
</div>

---

<!-- _class: ugm-default -->

# Quick Style Guide

### Default Layout (ugm-default)

- General content slides
- Most bullet points
- Text-heavy explanations
- Introductions and conclusions

### Inverted Layout (ugm-invert)

- Code demonstrations
- High-contrast emphasis
- Technical deep-dives
- Engagement breaks

---

<!-- _class: ugm-default -->

# Quick Style Guide

### Gradient Layout (ugm-gradient)

- Section headers
- Key announcements
- Feature highlights
- Major transitions

### Heading Layouts (heading-\*)

- Section breaks
- Topic introductions
- Major theme shifts
- Visual pacing

---

<!-- _class: ugm-default -->

# Copy This Section: Basic Content Template

Replace this with your own content. Keep the structure:

**Title**: Main heading using h1

**Subtitle or context**: Use h2 for additional structure

**Body content**: Regular paragraphs with Lexend Deca body text

- Bullet points for lists
- Clean visual hierarchy
- Easy to scan and read

---

<!-- _class: ugm-default -->

# Copy This Section: Card-Heavy Layout

<div class="card">

**Card 1 Title**

Brief description of key concept or information. Cards create visual blocks that organize related content.

</div>

<div class="card accent-cambridge">

**Card 2 Title**

Supporting information that relates to card 1. Use different accent colors to group related cards by theme.

</div>

<div class="card accent-azul">

**Card 3 Title**

Additional context or technical details. Cards are excellent for organizing multiple pieces of information clearly.

</div>

---

<!-- _class: ugm-default -->

# Copy This Section: Two-Column Format

<div class="columns">
<div>

## Left Side Title

- Bullet point one
- Bullet point two
- Bullet point three

This column works well for:

- Primary concepts
- Main arguments
- Key steps

</div>
<div>

## Right Side Title

This is a paragraph of explanatory text on the right side. You can also use:

- Bullet lists
- Numbered lists
- Small blocks of text
- Single images

</div>
</div>

---

<!-- _class: ugm-default -->

# Final Tips for Effective Presentations

1. **Consistency**: Use the same layout for similar content types
2. **Variety**: Mix layouts to maintain visual interest without exhausting viewers
3. **Hierarchy**: Use heading styles to establish clear structure
4. **Color**: Leverage the UGM palette for emphasis and organization
5. **Whitespace**: Don't overcrowd slides; use padding and margins generously
6. **Typography**: Fraunces for headings, Lexend Deca for body—never mix
7. **Testing**: Preview on the actual screen/projector before presenting

---

<!-- _class: ugm-invert -->

# Questions?

Feel free to:

- Copy any section from this master template
- Customize colors and spacing to fit your needs
- Combine layouts for unique presentations
- Share feedback on what works best

**Happy presenting! 🎉**
