# Documentation leveling test
This project consists of two main parts: an HTML file that structures the content and a CSS file that styles and formats the page, in addition to the assets.

## HTML
The document begins with the basic structure for an HTML file, defining the file type, with a simple <head> but with metadata and finally the <body> making use of the correct semantic tags I think.

### The <head> section includes essential tags such as:


<meta charset="utf-8" /> to define the character encoding.

<meta name="viewport" content="width=device-width, initial-scale=1.0"> to make the page responsive on mobile devices.

### The <body> the visible content is structured:

A <header> containing the navigation bar, photo, and name.

A <main> containing:

The "About Me" section with a brief description and lists of soft and technical skills, accompanied by images of the corresponding technologies.

The "Projects" section showing different projects with illustrative images of the code and menus.

A <footer> containing the contact section, including information, links, and a form for submitting messages.

## CSS
A fixed background color is set, and default margins and padding are removed from the body.

The navigation bar (.nav_bar) is sticky at the top, with colors and hover effects for the links.

The profile photo and name (.picture_name) are styled to center and round out the image with shadows and a border.

The #about_me section and the lists within .skills have styles to center text, remove periods from lists, and add space between items.

The skill images are responsive, displaying inline on large screens and centered on mobile devices (I copied this part from an example and it works, but I don't fully understand it).

The projects section (#projects) is centered and stylized, with a zoom effect and shadow on hover.

The contact information uses tables.

The contact form is centered and doesn't look bad.
