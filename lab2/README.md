# Lab 2: Web Fundamentals and Assistive Technologies

**Semantic HTML, CSS, and JavaScript are the core components that make web apps accessible.**  
The testing team has found accessibility defects in your code and asked for the issues to be corrected. Your task is to spot the bad coding and fix it.

---

## Objectives

In this lab, you will:  
- Recognize common accessibility issues in web code.  
- Apply basic HTML, CSS, and JavaScript understanding to fix accessibility issues.

---

## Instructions

### Prerequisites
- **Google Chrome**
- **Code Editor** (e.g., Visual Studio Code)
- **Colour Contrast Analyser (CCA)**

### References
- [HTML Element Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)  
- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)  
- [HTML Events Attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)  

### Steps
1. Analyze the code using Chrome Inspector.  
2. Identify issues in the code.  
3. Open the file containing the code in Visual Studio Code (or your chosen code editor).  
4. Correct the code to address the issue.  
5. Save the corrected file and validate your changes.  

---

## Questions

### **Question 1 - HTML**

You are provided with HTML code containing the following issues:
- **Unclosed paragraph tags**
- **Missing `alt` attributes in images**
- **Unclosed unordered list**

These errors make it challenging for assistive technologies to interpret the content properly.  

**Your task:**  
- Identify and correct the errors in the HTML code.  
- Use the [Markup Validation Service](https://validator.w3.org/) to validate the code.  
- Switch to "Validate by Direct Input" for validation.

---

### **Question 2 - CSS**

Your code contains:  
- An image used to display text, which is problematic for screen readers.  
- A list of links with no clear indication that they are links.  
- Difficulty in identifying which link is currently focused.

**Your task:**  
- Correct the issues to make the image accessible and improve link focus visibility.  

---

### **Question 3 - CSS & HTML**

The content includes:  
- A button with improper semantics, making it unrecognizable by screen readers.  
- Background and text colors that are difficult to see for persons with low vision.  

**Tools to Practice:**  
- Use **Colour Contrast Analyser (CCA)** to address color contrast issues.  
- Select color combinations that pass **WCAG 2.1 1.4.3 Contrast AA contrast ratio**.  

**Resources:**  
- [Tutorial: How to Use Colour Contrast Analyser (Video, 2m 33s)](https://www.section508.gov/training/web-software/andi-training-videos/color-contrast-analyzer/)  

---

### **Question 4 - JavaScript**

You are provided with a button that displays text when hovered over with a mouse pointer.  
**Accessibility Issue:**  
Keyboard-only users must also be able to display the text using the keyboard without relying on a mouse.

**Your task:**  
- Update the code to ensure keyboard-only users can interact with the button.  

---