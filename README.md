# Project 3: Spots

An image sharing site: https://dcdunn12.github.io/se_project_spots/

# Description

This project involves creating a responsive web page that adapts smoothly to various screen sizes, ranging from desktops to mobile devices. It utilizes the latest modern HTML and CSS practices, ensuring a seamless user experience while keeping users updated with current trends in web development.

The primary objective was to design a clean, user-friendly interface featuring an organized card layout. Flexbox was chosen for its flexibility in aligning and distributing space among items, which enhances the overall user experience.

# Tech Stack

With Flexbox, the cards automatically adjust to fit different screen sizes, maintaining a consistent design. This approach simplifies the alignment of items in a row or column, making it highly responsive, which is why I opted for it over CSS Grid. I also employed media queries in the cards.css file to adjust the layout for various screen resolutions.

For example, at smaller breakpoints, such as 768 pixels for tablets, the layout is rearranged into a single column to improve readability. You can observe how the cards stack on smaller screens and how the padding adjusts to fit the content on different devices.

In my index.html file, I used semantic tags like header, section, and footer. These tags enhance the structure of the HTML, making it easier for search engines and assistive technologies to interpret the content. Additionally, semantic tags improve code readability for developers.

The BEM methodology stands for Block Element Modifier. A block refers to a standalone component, such as a profile, while an element is a part of that block, like a "Profile Edit" button. A modifier changes the appearance, like "Profile Edit button Active." I organized my CSS file with this framework in mind, keeping blocks, components, and modifiers separated in the stylesheet to maintain clean and reusable code.

At the beginning of my stylesheet, I included a CSS normalization to ensure consistent default styling across different browsers. Fonts were linked early in the stylesheet to avoid any flashing of unstyled text and to ensure the content appears as intended from the moment the page loads.

I connected the fonts in my project using the @font-face rule and linked Google Fonts for easy access. Poppins was chosen as the primary font, with Arial and sans-serif as fallback options. This ensures the page maintains a similar look even if the primary font fails to load.

# Deployment

This webpage is deployed to github pages:
https://github.com/dcdunn12/se_project_spots.git

# Visual

Link to explanation of code: https://youtu.be/ckwsToOaZF0
