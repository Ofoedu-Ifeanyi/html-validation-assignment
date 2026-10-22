1. Missing document language

The opening <html> tag doesn't specify a language using lang.



2. Missing page title

There is no <title> element inside <head>.



3. Incorrect nesting

An <h1> is placed inside <head>. Visible page content belongs inside <body>.



4. Missing closing tags and incorrect nesting

Some paragraphs are not closed correctly, and one paragraph is closed after the surrounding <div>.



5. Incorrect heading hierarchy

The document jumps from <h1> to <h3> without a logical <h2> section heading.



6. Duplicate IDs

Two paragraphs use id="events". Each ID should be unique in the document.



7. Image missing alternative text

The <img> element has no alt attribute describing the garden image.



8. Potentially broken relative links

The image path images/garden.jpg and the link pages/about.html need to be checked against the files in your project.



9. Incorrect form-label associations

The name label points to fullname, but the input ID is name. The email label is also missing its for attribute.



10. Missing closing paragraph

The final contact paragraph is not closed before the document ends.