# summer-school-online-day-2

This project is a *personal profile card* created as part of the *Summer School Online - Day 2 Assignment*.  
The goal was to apply different types of CSS (Inline, Internal, and External) and practice various CSS selectors.

---

## ✅ Files Included
- index.html – Main HTML file that builds the profile card layout.
- style.css – External CSS file for styling.
- readme.txt – Explanation of CSS types and selectors used.

---

## 🎯 CSS Types Used

1. *Inline CSS*
   - Applied directly in the style attribute of HTML tags.
   - Example:  
     html
     <div class="profile-card" style="border: 2px solid #0077cc;">
     

2. *Internal CSS*
   - Included within a <style> tag inside the <head> of index.html.
   - Used to style overall layout, headings, bio, and contact sections.

3. *External CSS*
   - Defined in style.css and linked to the HTML using <link>.
   - Used for reusable styles, such as profile image formatting.

---

## 🧠 CSS Selectors Used

| Selector Type     | Example                         | Purpose                                 |
|-------------------|----------------------------------|-----------------------------------------|
| *Element*        | p, h1, ul                 | Targets all elements of that type       |
| *ID*             | #profile-pic                  | Targets the profile image by ID         |
| *Class*          | .bio, .contact              | Styles sections using class names       |
| *Group*          | h1, h2                        | Applies same style to multiple elements |
| *Descendant*     | .contact a, .contact p      | Styles elements nested inside a parent  |
| *Attribute*      | a[href]                       | Targets anchor tags that have href    |
| *Hover*          | .contact a:hover              | Changes link color on mouse hover       |

---

## ✨ Bonus Features
- *Hover Effect* on contact links (changes color when hovered).
- *Box Shadow & Border* applied to the card for a modern look.

---

This profile card displays:
- A name and profile image
- A short bio
- A list of hobbies
- Contact information (email and Instagram)

---
