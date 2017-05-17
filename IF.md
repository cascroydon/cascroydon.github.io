# Interactive Fiction Activity

* [Learning objectives](#learning)
* [Prerequisites](#prereq)
* [Resources](#resources)
* [Planning](#planning)
* [Writing](#writing)
* [Challenges](#challenges)
* [Testing](#testing)
* [Competition](#compo)
* [Example](#example)

## Learning Objectives {#learning}

After completing this activity students should be able to:
* describe the purpose of a markup language
* design a branching story
* create a hypertext document
* practise writing in the second person

## Prerequisites {#prereq}

To read and write HTML, students must be able to:
* type with a computer keyboard, including use of code symbols such as `< > { } & ; = " ' !`
* read and reproduce HTML keywords without introducing spelling errors
* create, move, and rename files including file extensions

It is helpful, but not essential, if students can:
* drag select text with the mouse
* copy and paste text with keys or menu options
* indent lines consistently
* use case (upper and lower case characters) consistently

Technical challenges:
* hosting on a school web server
* site and script blocking
* installing editors
* hidden file extensions

## Resources {#resources}

To run this activity you will need:
* an HTML editor, either
 * an online in browser editor with cloud storage, or
 * a standalone editor such as Brackets or Notepad, a separate browser, and storage for student projects
* pencil, eraser, and paper (for more complex stories)

## Planning {#planning}

For younger students, these stories can be very short with just a few choices. In this case, students can skip the planning stage and compose their stories directly in their editor.

For more complex stories, with 6 or more decisions to make, students will need to plan out their story structure on paper before attempting to create the files.

First, sketch out the passages in the story where the reader is offered a choice and join them up to make a graph. Each node in the graph represents a choice for the reader, and each connecting line represents a decision. In computer science terms this is a control flow graph and can be considered an algorithm.

## Writing {#writing}

Each passage will require a HTML file. Each HTML file will follow a simple structure:

    <!DOCTYPE html>
    <html>
        <body>
            <p>You are offered the choice:
            <a href="money.html">take the money</a> or 
            <a href="box.html">open the box.</a></p>
        </body>
    </html>
    
By convention, your start HTML page will be named `index.html`. After this each linked HTML page will need a unique name. Note, that links will be case sensitive so a good rule is to make all page file names lower case. If a file needs a longer name, use single dash characters to separate words, e.g. `donate-money.html`.

Typically you will write descriptive passages in the second person.

## Challenges {#challenges}

There are many ways to expand this activity for more advanced students:
* add illustrations
* style the fonts and page layout
* use cookies to remember state
* add random chances and battles

## Testing {#testing}

After completing their projects, students should get their peers to play their games. This will help them to discover bugs and issues with comprehension. Peers can provide feedback which students can address and this cycle can repeat until they are happy with their work.

## Competition {#compo}

There is an annual [interactive fiction competition](https://ifcomp.org/). I would encourage students who find this activity rewarding to enter their work.

## Example {#example}

Here is an example interactive fiction based on the Brothers Grimm tale <a href="TheWhiteSnake">The White Snake</a>. This version does include some CSS styles and a custom font, but other than that is plain HTML. The source files are available in <a href="https://github.com/cascroydon/TheWhiteSnake">this GitHub project</a>.