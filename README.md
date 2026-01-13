# CSS-Features

Learning CSS with practical examples and different implementation methods.

## Folder Structure

This repository contains CSS learning examples organized by different CSS implementation methods:

---

## External CSS

### Overview
External CSS is a method where CSS rules are written in a separate `.css` file and linked to the HTML document using the `<link>` tag in the `<head>` section. This is the most commonly used and recommended approach for styling web pages.

### Advantages
- **Separation of Concerns**: HTML structure and CSS styling are completely separated
- **Reusability**: The same CSS file can be linked to multiple HTML pages
- **Maintainability**: Easier to manage and update styles across the entire project
- **Performance**: CSS file is cached by the browser, improving load times for subsequent visits
- **Scalability**: Best practice for larger projects with multiple pages

### Files Included

#### 1. **netflix-login.html**
A Netflix-inspired login/signup page that demonstrates external CSS usage.

**Key HTML Elements:**
- Netflix logo created using SVG
- Sign-up form with input fields (First Name, Last Name, Email, Password, Confirm Password)
- Terms & Conditions checkbox
- Sign-up button
- "Already have an account?" link

**How it works:**
- Links the external CSS file using: `<link rel="stylesheet" href="./main.css">`
- References CSS classes for styling different elements (div-background, div-signup-box, input-text, button-signup, etc.)

#### 2. **main.css**
The external stylesheet that styles the Netflix login page.

**Key Styling Features:**

- **body**: Sets black background and Arial font family
- **.div-background**: Full viewport height with dark gradient overlay
- **.div-signup-box**: Centered signup form container using Flexbox
- **.input-text & .input-conpwd**: Dark-themed input fields with styling
- **.button-signup**: Netflix red (#e50914) button with hover cursor
- **.div-alreadyacc**: Centered "Already have an account?" section
- **.div-terms**: Terms checkbox styling

**CSS Techniques Used:**
- CSS Flexbox for layout and alignment
- Linear gradients for background effects
- Box-sizing for proper padding/width calculation
- Rgba colors for transparency effects


