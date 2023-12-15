
# Challenge 1: Semantic-Refactor Journey

## A study in refactoring HTML semantics  

As a student of the UC Berkeley Extension Boot Camp, I was given the weekly challenge (Challenge 1) of giving linked HTML and CSS files more appropriate semantics.  I made changes to the HTML and CSS code to reflect a more appropriate semantic structure.  I followed the acceptance criteria of Challenge 1 to modify the starter code until I was satisfied with my results.  I needed to make changes to the HTML starter code, then make the necessary changes in the CSS starter code to ensure the changes did not break the webpage.  As part of the challenge, the modified index.html file/webpage needed to look the same as the starter HTML code when opened in a web browser. There were other types of modifications I made, both within the HTML and CSS files, to create cleaner and more succinct code.

**Table of contents**
- [Motivation](#item-one)
- [What are the problems identified?](#item-two)
- [What are the solutions?](#item-three)
- [What was learned?](#item-four)
- [Usage](#item-five)
- [Credits](#item-six)
- [License](#item-seven)

___

<a id="item-one"></a>
### MOTIVATION ###

My motivation for the Semantic-Refactor Journey project was the desire to learn more appropriate semantic HTML structure.  As a "green" boot camp student with little to know preexisting knowledge of the topic, I want to learn appropriate ways to code HTML that have a semantic structure.  Within the week's time of working in this project, I also attended boot camp class.  During class time and office hours, I learned of other ways to make HTML and CSS code more "appropriate."  One such form of appropriate criteria to aim for in code is to do away with redundancies.  I was therefore, also motivated to learn to identify redundancies and comment them out of the code.  My final motivation was to learn to follow acceptance criteria.  Because I am in the boot camp to pursue a career change, I have a motivation to learn, implement, and follow actions of what a web developer would do, such as following the items of an acceptance criteria.  It was important for me that I learn to understand the items in the acceptance criteria, and use them as an overall motivation to help me complete this project.

<a id="item-two"></a>
### WHAT ARE THE PROBLEMS IDENTIFIED? ###

- Problems with the starter HTML code
  - Several division tags: <div>
    When looking at the starter HTML code, it was unclear at first what the div's represented.  I can imagine if the HTML code was dozens of times longer, looking at or analyzing the code may prove challenging if the majority of the tags were div's.  The majority of the problems of the starter HTML code therefore did not contain semantic HTML.
  - Missing tags: <div>
    The starter code had a missing main tag.   
  - Broken links: <div>
    The starter code had a link that did not work in the navigation bar.
  - Sequential numbering of tags: <div>
    A header 2 tag appeared after header 3 tags.  Therefore, the header 2 tag appeared in a non-sequential order.
  - Alternative text for images: <div>
    Alternative (alt) text did exist in the starter HTML code for images.  There were six images that did not include alt text, making this page less accessible for individuals with visual impairments who use screen readers to access the web.

- Problems with the starter CSS code
  - Changing names of classes: <div>
    When changes were made to tags in the starter HTML code to make it more semantic, changes in the CSS code needed to also be made so that selectors matched the new HTML tag.
  - Addressing redundancies: <div>
      - The header "Horiseon" held an unnecessary color property.  There was a seo class that contained a color property, which was written in the starter HTML code in the h1 line with a span tag.  This seemed unnecessary and challenging to read in the starter HTML code.  This problem was seen as a redundancy in the starter CSS code because of an identical color property.  This will be further explained in the following "What are the solutions?" section.
      - There were a few redundancies of properties that existed in classes.  For example, there were properties that were identical in the benefit image classes of the starter CSS code.

- Maintaining the original look of the web page: <div>
  - Finding and implementing solutions to all of the above mentioned problems created an      ongoing, overarching problem, in which the webpage would break when problem items were changed.  This created the overarching problem of trying to maintain the original look over the web page throughout my time working on this project.  This will be further explained in the following "What are the solutions?" section.

<a id="item-three"></a>
### WHAT ARE THE SOLUTIONS? ###

- Solutions to the starter HTML code
  - Solution to several division tags: <div>
    Div tags were replaced with the following tags (some in multiple instances) to create a more semantic HTML code: <div>
      - section
      - nav
      - aside
      - footer
  - Solution to missing tags: <div>
    Main tag was included in the HTML code to contain the main portion of the webpage.   
  - Solution to broken links: <div>
    The search-engine-optimization id was added on line 31 so that the href search-engine-optimization link would work when clicked.  Once this was added, the search-engine-optimization text in the navigational bar was a functioning link that brought the page down to the search-engine-optimization section of the webpage.
  - Solution to sequential numbering of tags: <div>
    The header tag h2 in the footer section was changed to h4 so that the header numbers followed a sequential order
  - Solution to alternative text for images: <div>
    Alternative (alt) text was added for the images of the webpage.  Brief descriptions were typed as alt text for these images.

- Solutions to the starter CSS code
  - Solutions to changing names of classes: <div>
    After making changes to HTML tags, changes to CSS classes were made to match the new HTML tags.
  - Solutions to addressing redundancies: <div>
      - The header "Horiseon" held an unnecessary color property.  This color property was moved into the header h1 class, and the header h1 seo class was commented out.  To ensure this color property still worked, the span element in the starter HTML code was deleted now that the color property would take effect in the HTML code because it was now within the CSS header h1 class.
      - Classes that contained properties that were identical could be consolidated into one class with a new class name.  There were multiple occasions on the CSS code where this occurred.  The example written in the "what are the problems identified" section stated there were three benefit image classes, but they all contained identical properties.  Therefore, two of these classes were commented out, and one was kept, but given a new class name.  In this example, the class name was changed to benefit-trio img.  The word "trio" was used because there were three images these properties were applied to in the HTML code.  To ensure the HTML code still functioned, this new class name was written in place of the old class names in the HTML code.

- Solutions to maintaining the original look of the webpage: <div>
  - The solution to maintaining the original look of the webpage can be seen in the image and active link in the "Usage" section.  This required a constant "back and forth" of looking at the HTML code, then the CSS code, and vice versa, to ensure that the code I changed in one was also changed in the other when necessary. For example, when one class name was changed in the CSS code, the class name was changed in the HTML code.

<a id="item-four"></a>
### WHAT WAS LEARNED? ###

At the start of this challenge, I had little to no understanding of HTML tags and elements, let alone what Semantic HTML should look like.  After google searching, reading articles, going to a tutor session provided by my boot camp, and most importantly working on part of this challenge with a classmate, I was able to complete the challenge.  In addition to learning what tags to use in HTML code to make the structure more semantic, I learned several other things including:
- How to "comb" code to look for redundancies.
- How to properly link CSS classes into HTML code.
- What certain HTML tags mean.
- How to comment out code.
- What HTML code with proper semantics should look like.
- How to collaborate with a classmate/colleague.
- How to write a README file.

<a id="item-five"></a>
### USAGE ###

The GitHub repository containing the HTML and CSS code that I edited can be found at the following [link](https://alexahnbaum.github.io/challenge_1_semantic_refactor_journey/)
![Alt text==a screenshot of Challenge 1 HTML page for the README file](<assets/images/Screenshot%202023-12-10%20at%2011.01.42 AM.png>)

<a id="item-six"></a>
### CREDITS ###

I had one collaborator on this challenge.  This collaborator was my boot camp classmate, Keegan Royal-Eisenberg.  We worked together in the beginning stages of the challenge. 

I read the following articles to find information relevant to helping me complete this challenge.
- [Semantic HTML for meaningfu HTML](https://seekbrevity.com/semantic-markup-important-web-design/#:~:text=Semantic%20markup%20is%20a%20way,content%20rather%20than%20its%20appearance.&text=Writing%20semantic%20markup%20means%20understanding,and%20machines%20will%20read%20it)
- [W3 Schools: Semantic HTML Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [W3 Schools: How to add CSS](https://www.w3schools.com/css/css_howto.asp)
- [How to Write a Good README File for your GitHub Project](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)
- [Professional README Guide](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide)
- [Markdown Table of Contents: How to Create One](https://www.eddymens.com/blog/markdown-table-of-contents-toc-how-to-create-one)

<a id="item-seven"></a>
### LICENSE ###

No license was created for this project because it was a challenge for the boot camp I am enrolled in.