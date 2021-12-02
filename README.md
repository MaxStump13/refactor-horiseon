# refactor-horiseon
## Description
Provide a short description explaining the what, why, and how of your project. Use the following questions as a guide:
- What was your motivation?
- Why did you build this project? (Note: the answer is not "Because it was a homework assignment.")
- What problem does it solve?
- What did you learn?
A marketing agency wanted to make an already existing webpage more accessible and optimized for search engines. Opening the source code of the page, I immediately noticed there were no semantic HTML elements or alternative texts for images (alt). With further investigation, I noticed the heading elements were not sequentially ordered and one link in the navigation didn’t work. So, I changed all <div> elements with semantic HTML elements relative to their position and function. Next, I added a title and alt tags to each image to increase accessibility. Then, I changed the heading elements so they were ordered <h1> at the top to <h4> at the bottom. Next, I added an ID tag to the “search engine optimization” section, fixing the broken navigation link. Lastly, I added comments to the code to make it more readable for future reference. I learned it was possible to add alternative text to the html elements for background images in the CSS file.

## Table of Contents (Optional)
If your README is long, add a table of contents to make it easy for users to find what they need.
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
## Installation
N/A
## Usage
Provide instructions and examples for use. Include screenshots as needed.
To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:
    ```md
    ![alt text](assets/images/screenshot.png)
    ```
## Credits
https://www.w3schools.com/html/default.asp
https://www.w3schools.com/css/default.asp
https://developer.mozilla.org/en-US/docs/Web/HTML

List your collaborators, if any, with links to their GitHub profiles.
If you used any third-party assets that require attribution, list the creators with links to their primary web presence in this section.
If you followed tutorials, include links to those here as well.
## License
N/A

The last section of a high-quality README file is the license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, refer to [https://choosealicense.com/](https://choosealicense.com/).
---
🏆 The previous sections are the bare minimum, and your project will ultimately determine the content of this document. You might also want to consider adding the following sections.
## Badges
N/A

![badmath](https://img.shields.io/github/languages/top/nielsenjared/badmath)
Badges aren't necessary, per se, but they demonstrate street cred. Badges let other developers know that you know what you're doing. Check out the badges hosted by [shields.io](https://shields.io/). You may not understand what they all represent now, but you will in time.
## Features
If your project has a lot of features, list them here.

Working navigation in header
Alternative text and semantic HTML elements for accessibility

## How to Contribute
If you have any addition ideas or would like to contribute, my GitHub is https://github.com/MaxStump13.

If you created an application or package and would like other developers to contribute it, you can include guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own if you'd prefer.
## Tests
N/A
Go the extra mile and write tests for your application. Then provide examples on how to run them here.