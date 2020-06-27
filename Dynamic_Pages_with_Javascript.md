-[Return to Home](/README.md)

# Learning Journal
*Blog Entry-* Lab 06

## Dynamic Pages with Javascript

Webpages are made up of three different layers.  The first layer is the **Content** layer, written in HTML, which contains the text, images, videos, and other content of the page.  The second layer is the **Presentation** layer, written in CSS, which changes how the content is presented.  The third layer is sthe **Behavior** layer, written in JavaScript, which sets how the behaves and interacts with you.

### Basic Anatomy of JavaScript
JavaScript is essentially a series of **statements** that tell the computer what to do.  Additional code tells the computer when it is done reading and performing the statements.

Statements each get their own line and end with a semicolon.  If surrounded by curly braces, statements are called **code blocks**.

#### Variables
One type of statement is a **variable**.  Variables temporarily store information to be used in later code.  Variables are initiated by using the *keyword* "var" and a name you assign.  This is called **declaring** the variable.

**Variable Names** can be whatever you want, as long as they follow these rules:

- If it's more than one word, the first word is lowercase and all remaining words have their first letter capitalized.
- The name can contain letters, numbers, $, and _ anywere in the name. EXCEPT:
    - It can never start with a number.
    - It can never have a dash or a period.
- Never used JavaScript *keywords* or *reserved* words.  Find these online.

Variables are assigned **value** using an *equal sign* (=) in a statement.  Their value can be one of 3 **data types**:

1. **Numeric:** positive numbers, negative numbers, and decimals
2. **String:** letters and other characters surrounded by single quotes or double quotes.  Never use one of each in a statement. Use one or the other.
3. **Boolean:** true or false