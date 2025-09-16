Below is the improved Markdown file incorporating the CSS properties notes from your previous input, along with a new section for the "CSS Day 2 Homework" that emphasizes enhancing an HTML portfolio project using the listed CSS properties. I've refined the text for clarity, structure, and professionalism while maintaining the original content's intent.

<xaiArtifact artifact_id="4716196b-a163-4fcf-90eb-cdc8dc2717f6" artifact_version_id="5758844c-3a63-4590-970b-3aa79a70f60d" title="css_properties_notes.md" contentType="text/markdown">

# CSS Properties Guide & Portfolio Homework

This document provides a comprehensive guide to key CSS properties and includes a homework assignment to enhance your HTML portfolio project using these properties.

## CSS Properties Reference

### 1. **width**
- **Purpose**: Defines the width of an element.
- **Units**: Accepts `px`, `%`, `vw`, `rem`, `em`, etc.
- **Example**: `width: 90px;` sets the element's width to 90 pixels.
- **Portfolio Use**: Use `width` to control the size of sections like project cards or images in your portfolio.

### 2. **height**
- **Purpose**: Sets the height of an element.
- **Units**: Supports `px`, `%`, `vh`, `rem`, `em`, etc.
- **Example**: `height: 90px;` fixes the element's height at 90 pixels.
- **Portfolio Use**: Apply `height` to create consistent image or button sizes for a polished look.

### 3. **margin**
- **Purpose**: Adds space outside an element's border.
- **Options**: Set for all sides (`margin: 10px;`) or individually (`margin-top: 20px;`).
- **Example**: `margin-left: 30vw;` positions the element 30% of the viewport width from the left.
- **Portfolio Use**: Use `margin` to space out sections, such as between navigation links or project descriptions.

### 4. **padding**
- **Purpose**: Adds space inside an element, between content and border.
- **Options**: Apply to all sides (`padding: 10px;`) or individually (`padding-top: 20px;`).
- **Example**: `padding: 0.5%;` sets padding to 0.5% of the element's width.
- **Portfolio Use**: Add `padding` to buttons or content containers for better readability and aesthetics.

### 5. **border**
- **Purpose**: Defines an element's border style, width, and color.
- **Shorthand**: Combines `border-width`, `border-style`, and `border-color`.
- **Example**: `border: 1px solid black;` creates a 1-pixel wide, solid black border.
- **Portfolio Use**: Use `border` to highlight project cards or create decorative outlines around images.

### 6. **color**
- **Purpose**: Sets the text color of an element.
- **Values**: Accepts color names, hex codes, RGB, HSL, etc.
- **Example**: `color: pink;` makes the text pink.
- **Portfolio Use**: Apply `color` to headings, links, or text to match your portfolio’s theme.

### 7. **background-color**
- **Purpose**: Sets the background color of an element.
- **Values**: Supports color names, hex codes, RGB, HSL, etc.
- **Example**: `background-color: black;` sets a black background.
- **Portfolio Use**: Use `background-color` for section backgrounds or navigation bars to enhance visual hierarchy.

### 8. **font-family**
- **Purpose**: Specifies the font for an element's text.
- **Fallbacks**: Include fallback fonts (e.g., `font-family: cursive, sans-serif;`).
- **Example**: `font-family: cursive;` applies a cursive font style.
- **Portfolio Use**: Choose a professional `font-family` for headings and body text to ensure readability.

### 9. **font-weight**
- **Purpose**: Controls the thickness of the font.
- **Values**: Includes `normal`, `bold`, or numeric values (e.g., `100` to `900`).
- **Example**: `font-weight: 900;` sets a very bold font.
- **Portfolio Use**: Use `font-weight` to emphasize headings or key text in your portfolio.

### 10. **text-transform**
- **Purpose**: Modifies the capitalization of text.
- **Values**: Includes `uppercase`, `lowercase`, `capitalize`.
- **Example**: `text-transform: uppercase;` converts text to all uppercase.
- **Portfolio Use**: Apply `text-transform` to navigation links or section titles for stylistic effect.

### 11. **box-sizing**
- **Purpose**: Determines how an element’s width and height are calculated.
- **Key Value**: `border-box` includes padding and border in the element’s dimensions.
- **Example**: `box-sizing: border-box;` ensures consistent sizing across elements.
- **Portfolio Use**: Set `box-sizing: border-box;` globally to simplify layout calculations.

### 12. **text-decoration**
- **Purpose**: Controls text decorations like underline or strikethrough.
- **Common Value**: `none` removes decorations.
- **Example**: `text-decoration: none;` removes underlines from links.
- **Portfolio Use**: Use `text-decoration` to style links for a clean, modern appearance.

### 13. **list-style**
- **Purpose**: Customizes the appearance of list items.
- **Common Value**: `none` removes bullets or numbers.
- **Example**: `list-style: none;` eliminates default list markers.
- **Portfolio Use**: Apply `list-style: none;` to navigation menus for a sleek, custom look.

## CSS Day 2 Homework: Enhance Your HTML Portfolio

### Objective
Improve your existing HTML portfolio project by applying the CSS properties listed above to create a visually appealing and user-friendly design. Your portfolio should showcase your skills, projects, and personal brand in a professional manner.

### Instructions
1. **Review Your Portfolio**:
   - Ensure your HTML portfolio includes key sections like a navigation bar, about section, project showcase, and contact information.
   - Identify areas where the design can be enhanced using the CSS properties above.

2. **Apply CSS Properties**:
   - **Navigation Bar**:
     - Use `margin` and `padding` to space out navigation links (e.g., `margin-left: 5px; padding: 0.5%;`).
     - Apply `text-transform: uppercase;` and `text-decoration: none;` for clean, bold links.
     - Set `font-family: cursive;` or a professional font and `font-weight: 900;` for emphasis.
     - Use `background-color` and `color` to create contrast (e.g., black background with pink text).
   - **Project Section**:
     - Create project cards with `width` and `height` to ensure consistent sizing.
     - Add `border` with unique styles (e.g., `border: 1px double aqua;`) and `border-radius` for rounded corners.
     - Use `margin` to space out cards (e.g., `margin: 90px;`).
     - Apply `background-color` to differentiate sections or highlight projects.
   - **Global Styling**:
     - Set `box-sizing: border-box;` globally to simplify layout calculations.
     - Remove default styles with `margin: 0;`, `padding: 0;`, `list-style: none;`, and `text-decoration: none;`.

3. **Enhance Visual Appeal**:
   - Experiment with `color` and `background-color` to create a cohesive color scheme.
   - Use `font-family` and `font-weight` to establish a clear text hierarchy.
   - Apply `text-transform` and `border` creatively to add personality to your portfolio.

4. **Test and Refine**:
   - Test your portfolio on different screen sizes to ensure responsiveness.
   - Adjust `margin`, `padding`, `width`, and `height` as needed for balance and alignment.
   - Ensure `list-style: none;` and `text-decoration: none;` are applied to navigation for a clean look.

### Example Application
Based on the provided CSS code:
- **Navigation Links**:
  - Apply `.nav-links` styles with `margin-top: 20px; margin-left: 30vw;` to center the navigation.
  - Style links with `color: pink; background-color: black; font-family: cursive; text-transform: uppercase;`.
- **Project Cards**:
  - Use `.box` styles with `width: 90px; height: 90px; background-color: pink; border-radius: 20% 10% 30% 50%;` for unique card shapes.
  - Add `margin-top: 90px; margin-left: 90px;` for spacing.
- **Custom Elements**:
  - Apply `.mera-nunu` with `border: 1px solid black;` for specific sections or divs.

### Submission
- Update your HTML portfolio with the improved CSS.
- Ensure all listed properties (`width`, `height`, `margin`, `padding`, `border`, `color`, `background-color`, `font-family`, `font-weight`, `text-transform`, `box-sizing`, `text-decoration`, `list-style`) are used meaningfully.
- Share the updated project files or a live demo link for review.

</xaiArtifact>
