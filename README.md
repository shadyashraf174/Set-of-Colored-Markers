# **Colored Markers** 
#### Learned it from [freeCodeCamp](https://www.freecodecamp.org/) || See it Live at [CodePen](https://codepen.io/shady-ashraf/pen/dyxEyoZ)
###### Selecting the correct colors for your webpage can greatly improve the aesthetic appeal to your readers. In this course, you'll build a set of colored markers. You'll learn different ways to set color values and how to pair colors with each other.
---
### **Overview**
The **Colored Markers** project is a web-based visual demonstration of CSS styling techniques. It showcases color gradients and box shadows applied to elements to resemble marker pens. The project emphasizes the creative use of CSS properties, such as gradients, shadows, and layout styling.

---

### **Table of Contents**
1. [Project Structure](#project-structure)
2. [HTML Details](#html-details)
3. [CSS Details](#css-details)
4. [How to Use](#how-to-use)
5. [Summary of Selectors Used](#Summary-of-Selectors-Used)

---

### **Project Structure**
The project consists of two main files:
- `index.html`: Defines the structure and elements of the webpage.
- `styles.css`: Contains the styles for the marker elements, using CSS properties like gradients and box shadows.

File structure:
```
/
├── index.html
├── styles.css
```

---

### **HTML Details**
The `index.html` file sets up:
1. **Page Title:** The title is set to "Colored Markers."
2. **Main Heading:** `<h1>` tag displays "CSS Color Markers."
3. **Markers:** A container div houses three marker elements:
    - Red Marker
    - Green Marker
    - Blue Marker
4. **Marker Structure:** Each marker consists of:
    - `div.cap`: Represents the cap of the marker.
    - `div.sleeve`: Represents the body of the marker.

---

### **CSS Details**
The `styles.css` file applies custom styles to create the marker effect. Key points include:

#### General Styles:
- **Text Alignment:** The `<h1>` is centered using `text-align: center`.
- **Container Styling:** The `.container` has a white background with padding.

#### Marker Styles:
1. **Dimensions:** Markers are styled with a `width` of `200px` and `height` of `25px`.
2. **Cap and Sleeve:**
   - `.cap` width: `60px`
   - `.sleeve` width: `110px`
   - Both use `display: inline-block` for horizontal alignment.
3. **Gradients and Shadows:**
   - The `.red`, `.green`, and `.blue` classes use `linear-gradient` for a three-color effect.
   - Each has a `box-shadow` to simulate a glow.

Example for the red marker:
```css
.red {
    background: linear-gradient(rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));
    box-shadow: 0 0 20px 0 rgba(83, 14, 14, 0.8);
}
```

---

### **How to Use**
1. **Clone the Project:**
   ```bash
   git clone https://github.com/shadyashraf174/Set-of-Colored-Markers
   cd colored-markers
   ```
2. **Open the Project:**
   Open `index.html` in a browser to view the styled markers.

3. **Customization:**
   - Modify `styles.css` to change colors, gradients, or shadows.
   - Add new markers by duplicating and editing `<div class="marker">`.

---

### **Summary of Selectors Used**

- **Universal Selectors**: `body` - applies background image and font across the entire page.
- **Element Selectors**:
  - `h1`, `h2`, `p` - styles for headings and paragraphs, including font size, margins, and text alignment.
  - `img` - centers images within the page.
  - `hr` - styles horizontal lines separating sections.
- **Class Selectors**:
  - `.menu` - main content container for layout and background color.
  - `.established` - styles the "Est. 2020" text in italics.
  - `.bottom-line` - adds margin above the footer’s horizontal line.
  - `.item` - styles individual menu items, aligning flavor/dessert names with prices.
  - `.flavor`, `.dessert` - left-aligns menu item names and sets width.
  - `.price` - right-aligns prices with a specific width.
- **Footer and Link Selectors**:
  - `footer` - sets font size for footer text.
  - `.address` - adds margin to the bottom of the address in the footer.
  - `a`, `a:visited`, `a:hover`, `a:active` - styles links to ensure a consistent color scheme, with specific colors for hover and active states.
---

![image](https://github.com/user-attachments/assets/1853fabf-7549-4d26-8f08-566009605e0a)

---
