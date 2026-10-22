# HTML Validation: Problem and Fix Table

| Problem Found => Location in broken.html => Fix Applied in fixed.html => Why the Fix Matters |
| Missing document language | Opening `<html>` tag | Added `lang="en"` | Helps screen readers and browsers identify the page language. |
| Missing page title | Inside `<head>` | Added `<title>Community Garden</title>` | Gives the page a meaningful browser-tab title and helps search engines. |
| Heading incorrectly placed inside `<head>` | Inside `<head>` | Moved the main heading into the `<body>` | Keeps document metadata separate from visible page content. |
| Missing closing paragraph tag | First paragraph in the body | Added the missing `</p>` | Ensures the paragraph is properly closed. |
| Incorrect element nesting | Paragraph and `<div>` around the garden description | Corrected the paragraph structure | Prevents invalid HTML nesting and unpredictable browser interpretation. |
| Incorrect heading hierarchy | `<h1>` followed by `<h3>` | Changed the section heading to `<h2>` | Creates a more logical document outline for readers and assistive technology. |
| Duplicate IDs | Two paragraphs using `id="events"` | Gave each paragraph a unique ID | IDs should be unique so links, scripts, and styles target the correct element. |
| Image missing alternative text | `<img>` element | Added descriptive `alt` text | Helps screen-reader users understand the meaningful image. |
| Relative image path may be broken | `images/garden.jpg` | Kept the path and added alternative text | The image file must exist at the specified location for the image to load. |
| Relative link may be broken | `pages/about.html` | Changed the link to `about.html` | The link must point to the correct location of the destination page. |
| Missing form-label association | Name label and input | Matched `for="fullname"` with `id="fullname"` | Associates the label with the correct input for accessibility. |
| Email label missing association | Email label and input | Added `for="email"` to the label | Helps users and assistive technology identify the email field. |
| Missing closing paragraph tag | Final contact paragraph | Added `</p>` | Ensures the contact paragraph is properly closed. |
| Missing document structure | Main page content | Added `<header>`, `<main>`, and `<section>` elements | Gives the page a clearer, more meaningful structure. |
| Missing form field names | Name and email inputs | Added `name` attributes | Allows the fields to be identified when form data is submitted. |
| Incomplete page metadata | Inside `<head>` | Added the viewport meta element | Helps the page display appropriately on mobile devices. |

## Validation Results

- **Original file:** `broken.html` — contained HTML errors and warnings.
- **Corrected file:** `fixed.html` — passed the W3C Nu HTML Checker with no errors or warnings.
