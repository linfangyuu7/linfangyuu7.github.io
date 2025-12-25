# Headings  
To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the hierarchy level and typeface size of the heading.

# A first-level heading
## A second-level heading
### A third-level heading

# Quoting text
You can quote text with a >.

Text that is not a quote

> Text that is a quote


Quoted text is indented with a vertical line on the left and displayed using gray type.

# Links
You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ).

This site was built using [GitHub Pages](https://pages.github.com/).

## Section links
You can link directly to any section that has a heading. To view the automatically generated anchor in a rendered file, hover over the section heading to expose the  icon and click the icon to display the anchor in your browser.

The code block below demonstrates the basic rules used to generate anchors from headings in rendered content.
'''
# Example headings

## Sample Section
Test 1

## This'll be a Helpful Section About the Greek Letter Θ!
A heading containing characters UTF-8 character.

# Links to the example headings above

Link to the sample section: [Link Text](#sample-section).

Link to the helpful section: [Link Text](#thisll-be-a-helpful-section-about-the-greek-letter-Θ).

'''

# Color using LaTEX
$\color{red}{\text{Your text here}}$
**Note**: You must use \text because by default everything is a math symbol in LaTeX. 
