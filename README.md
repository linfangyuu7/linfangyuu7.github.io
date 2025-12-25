# Headings  
To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the hierarchy level and typeface size of the heading.
```
# A first-level heading
## A second-level heading
### A third-level heading
```
# Line breaks
```
This example
Will span two lines
```

However, if you are writing in an .md file, the example above would render on one line without a line break. To create a line break in an .md file, you will need to include one of the following:

1. Include two spaces at the end of the first line.
```
This example  
Will span two lines
```

2. Include an HTML single line break tag at the end of the first line.
```
This example<br/>
Will span two lines
```
3. Otherwise, you can leave a blank line between two lines
```
This example

Will have a blank line separating both lines
```

# Quoting text
You can quote text with a >.

Text that is not a quote

`> Text that is a quote`
> Text that is a quote


Quoted text is indented with a vertical line on the left and displayed using gray type.

# Quoting code
You can call out code or a command by wrapping it within single backticks.  

Example: 
```
Use `git status` to list all new or modified files that haven't yet been committed.
```
Use `git status` to list all new or modified files that haven't yet been committed.

# Links
You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ).

This site was built using [GitHub Pages](https://pages.github.com/).

## Section links
You can link directly to any section that has a heading. To view the automatically generated anchor in a rendered file, hover over the section heading to expose the  icon and click the icon to display the anchor in your browser.

The code block below demonstrates the basic rules used to generate anchors from headings in rendered content.
```
## Sample Section
Test 1

Link to the sample section: [Link Text](#sample-section).

```

## Relative links
You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

A relative link is a link that is relative to the current file. For example, if you have a README file in root of your repository, and you have another file in docs/CONTRIBUTING.md, the relative link to CONTRIBUTING.md in your README might look like this:
```
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```

## Images
You can display an image by adding ! and wrapping the alt text in [ ]. Alt text is a short text equivalent of the information in the image. Then, wrap the link for the image in parentheses ().
```
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)
```
When you want to display an image that is in your repository, use relative links instead of absolute links.


## Custom anchors
You can use standard HTML anchor tags (`<a name="unique-anchor-name"></a>`) to create navigation anchor points for any location in the document. To avoid ambiguous references, use a unique naming scheme for anchor tags, such as adding a prefix to the name attribute value.

You can link to a custom anchor using the value of the name attribute you gave the anchor. The syntax is exactly the same as when you link to an anchor that is automatically generated for a heading.

For example:
```
# Section Heading

Some body text of this section.

<a name="my-custom-anchor-point"></a>
Some text I want to provide a direct link to, but which doesn't have its own heading.

(… more content…)

[A link to that custom anchor](#my-custom-anchor-point)
```

# Color using LaTEX
$\color{red}{\text{Your text here}}$
**Note**: You must use \text because by default everything is a math symbol in LaTeX. 
