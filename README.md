# Code Refactor for a Marketing Agency

## Description

The purpose of this project was to refactor the existing code for a marketing agency, Horiseon, to become more accessible. While the starting code functioned correctly, it lacked key features such as semantic HTML elements, alt attributes for each image, and a concise title.

The starting code for the project contained repeated CSS. I consolidated the CSS by identifying redundant classes that could be combined into a single class, creating new ids when necessary, and applying CSS properties to elements, where possible, so that unneeded classes could be removed. I also organized the CSS to parallel the logical structure of the semantic HTML elements so that the code can be easily maintained.

Because there were so many CSS classes used in the starting code, a challenging aspect of this project was identifying what each class was intended to style. A class could not be simply turned into an id without understanding exactly what the class modified, otherwise some unwanted effects would result.

In the starting code, the navigation link to "Search Engine Optimization" was broken. I resolved this issue by creating an id for the specific content further down the page, removing the existing class, and creating a new class with consolidated CSS so that everything would still function properly.

Perhaps the greatest accomplishment of this project was consolidating the CSS from 201 to 131 lines of code, deleting 70 lines that were repetitious.

Please find the deployed application here: https://vruss14.github.io/marketing-agency-code-refactor/

## Installation

No installation steps are required to view this project. To view the front-end application, visit the URL above. The application's source code can be found on GitHub here: https://github.com/vruss14/marketing-agency-code-refactor

## Usage

This web application is designed for desktop. Thus, viewing this application at a resolution smaller than 768px may result in a sub-optimal user experience.

Please find a screenshot of the deployed application below:

![screenshot of Horiseon webpage](assets/images/horiseon-screenshot.png)

## Credits

Source code belongs to the Michigan State University Coding Bootcamp repository on GitLab, which requires authorization to view. For more information about the MSU Coding Bootcamp, please visit: https://bootcamp.msu.edu/




