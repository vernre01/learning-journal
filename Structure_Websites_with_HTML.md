-[Return to Home](/README.md)

# Learning Journal
*Blog Entry-* Lab 04

## Structuring Websites with HTML

### Process & Design
When designing a website, you must always ask who is actually going to use the website (your audience) and how are they going to use it.  Your audience could be a specific demographic or company.  Next, determine what information they needs and how often they will visit.

Keep this information at the forefront of your mind as you move forward.

#### Site Map
Develop the site's sturcture using a method called card sorting, where each piece of information is placed on its own piece of paper and then organized into a site map diagram.  Site map diagrams have a home, a main menu, and sub menus beneath each main menu.  

#### Wireframes
Draw a quick wireframe.  Wireframes tell you, generally, how you want to organize the content of the webpage. 

#### Visual Heirarchy
Use visual heirarchy, how eyes are drawn to some content before others, to organize content to be easily skimmable.  Larger text, brighter colors, unique styles, and images are all examples of things that draw people's attention first.

#### Similarity and Grouping
The human eye can be clued into content being similar using a variety of visual grouping methods, including proximity, recognizeable patterns (closure), lines &amp; curves (continuance), white space, color, and borders.

#### Navigation
Good navigation selectively shows only sections or content of the site, provides context of where you are in the site, and is concise, clear, interactive, and consistent.

### HTML5
**HTML5** is the newest html language.  It has introduced a number of new elements to divide up the page, instead of using **&lt;div&gt;**, that are more descriptive about the content they contain.  

These new elements include:
- **&lt;header&gt;-** Used for the main header of the page or headers within **&lt;article&gt;** or **&lt;section&gt;** elements.
- **&lt;footer&gt;-** Used for the main footer of the page or footers within **&lt;article&gt;** or **&lt;section&gt;** elements.
- **&lt;nav&gt;-** Contains navigational links to other pages in the site or to outside content.
- **&lt;article&gt;-** Contains page content that could stand on its own, say for publication.
- **&lt;aside&gt;-** Provides related content or links to it, but not the actual content.
- **&lt;section&gt;-** Intended for related content and typically has its own heading.
- **&lt;hgroup&gt;-** Groups heading tags together so they are treated like they're a single heading.
- **&lt;figure&gt;-** Can contain related images, videos, graphs, diagrams, code samples, or text.  Always needs to include a text description of the content within a **&lt;figcaption&gt;** element.
- **links-** One new way to use links is around larger block-level elements, not just one element.

***Note:*** Older browsers will not understand the new HTML5 elements are **block** not **inline**.  Some will also not allow the CSS rules to apply to the new elements.  You will need to create code in JavaScript to account for this.

### Extra Markup

#### DOCTYPE
The DOCTYPE element tells the browser which HTML language you're using.  To specifiy HTML5, use the DOCTYPE: &lt;!DOCTYPE html&gt;.

#### Comments
Adding comments to your code helps others reviewing your code, as well as yourself, easily understand the code.  It is common to see code indicating the beginning and end of sections. Comments are not visible to people viewing your website.  Do this by typing &lt;!-- and --&gt; on either side of your comment.

#### Identifying Elements
Elements can be identified using two different attributes, **id** and **class**.  Use **id** as a unique identifier for a single element. Use **class** when you wish to identify several elements together as being different from the other elements on the page.  Elements can be assigned to several **class** attributes by separating classes with a space.

#### Block &amp; Inline Elements
Simply put, **block** elements each start on a new line, whereas **inline** elements continue on the same line as their neighboring elements.  Some elements are inherintly **block** elements and some are **inline** elements.

You can group several elements &amp; text together in a **block** box by using the **&lt;div&gt;** elements.  Using **&lt;span&gt;** also groups elements &amp; text together, but as an **inline** box.

#### IFrames
When you want to create a little window to another website on your own website, use the **iframe** element. For instance, you might use this to include a Google Map on your website.

#### Meta
The **&lt;meta&gt;** elements allows coders to add useful information about the webpage, including a *description* of the contents, *keywords* to help search engines, information for search engines about whether or not to *include a page in search results*, who the *author* is, and how long a browser should *store the page locally* on the computer to save downloading time in the future.

#### Escape Characters
Some special characters are saved exclusively for use in HTML code.  In order to use these characters in regular text, special **escape characters** are used.  For a full list of **escape characters**, visit [here](https://www.freeformatter.com/html-entities.html).