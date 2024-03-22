 ### What is Markdown?

  First things first, let's consider what Markdown actually is.

  Markdown - is a lightweight, easy-to-read, easy-to-write plain text format
  for styling all forms of writing around the Internet. Markdown helps to
  control the display of the document: formatting words as bold or italic,
  adding images, creating lists and so on.

  Markdown was made by [John Gruber](http://daringfireball.net/) in 2004,
  with significant collaboration from [Aaron
  Swartz](http://www.aaronsw.com/).

  Markdown can be written in a basic text editor. It's an easy way to write
  text that easily translates into HTML. When you write in Markdown, you
  have to save the document with the .md or .markdown extensions.

  We can use Markdown almost everywhere:

   » StackOverflow uses Markdown for posts and comments.
   » GitHub uses Markdown for discussions in issues and pull requests.
   » Reddit uses Markdown for formatting comments.
   » Slack, Gitter and other IM use Markdown for formatting messages.
   » Jekyll, Octopress, Hexo and other static site tools use Markdown.
   » GitBook uses Markdown for writing books.
   » Many people prefer to use Markdown for writing their blogs.
   » Documentations for many open source project are written in Markdown.
   » how-to-markdown also uses Markdown for formatting exercises.

  So, knowledge of Markdown is an important skill for modern developers.
  That's why you have to learn it.

 ### How to get Markdown?

  There is no clearly defined Markdown standard. Markdown is just common
  rules on how to write readable and formatted text.

  While Markdown is a minimal markup language and is easily read and edited
  with a normal text editor, there's no need in specially designed editors
  for writing files in Markdown. However, there are a few editors that
  preview the files with styles.

  Implementations of Markdown are available for over a dozen programming
  languages (JavaScript, Ruby, Python, PHP, Perl, etc). In addition, many
  platforms and frameworks support Markdown out of the box. For example,
  Markdown plugins exist for every major blogging platform.

 ### How to use this workshopper?

  It's easy to use this workshopper. In most cases, it's enough to use these
  three commands for interacting with this workshopper:

   » how-to-markdown run file.md will serve a local server at
     http://localhost:3000/ with a preview of file.md.
   » how-to-markdown verify file.md will verify your file.
   » how-to-markdown help shows a help message.

   ## HEADINGS (Exercise 2 of 12)

  It's important to categorize information. That's when headings help.

  If you need to add a heading, just type a # sign at the beginning of the
  line. The number of # is a heading level. For example:

     # Heading 1
     ## Heading 2
     ### Heading 3
     #### Heading 4
     ##### Heading 5
     ###### Heading 6

  As in HTML, there are 6 levels of headings. These headings will be
  transformed into <h1>-<h6> tags accordingly.

  There are aliases for first and second-level headings. You will get a
  first-level heading if you type three = signs on the following line. You
  can type three - on the following line to create a second-level heading.
  For example:

     Heading 1
     ===

     Heading 2
     ---
# How To Markdown

 ## EMPHASIS (Exercise 3 of 12)

  It's easy to mark text as italic, bold, combined and strikethrough. There
  are a few ways to make emphasis in Markdown and each of those is readable.

  To get emphasis just wrap some text in single, double or triple asterisks
  (*) or underscores (_). Here are some examples:

     Italics with *asterisks* and _underscores_.

  |> Italics with asterisks and underscores.

     Bold with **asterisks** or __underscores__

  |> Bold with asterisks or underscores

     Combined emphasis with **asterisks and _underscores_**.

  |> Combined emphasis with asterisks and underscores.

  Sometimes you need to draw line through the text. To get strikethrough
  wrap the text in two tildes (~) like so:

     ~~Scratch this line.~~

  |> Scratch this line.

  ## LISTS (Exercise 4 of 12)

  Lists are important for structured information. There is nothing hard in
  the creation of lists in Markdown. Just insert an asterisk (*) or a dash
  (-) before each item for an unordered list or a number with a dot for an
  ordered one (e.g., 1., 2., 3.).

 ### Unordered lists

  Here is an example of an unordered list:

     * item1
     * item2
     * item3

  And it will be transformed to something like this:

   » item1
   » item2
   » item3

  Dashes work as well:

     - first item with dash
     - second item with dash

  Goes to:

   » first item with dash
   » second item with dash

 ### Ordered lists

  Here is an example of a simple ordered list:

     1. item1
     2. item2
     3. item3

  Which will be transformed into:

   1. item1
   2. item2
   3. item3

  As you may see, this notation is very intuitive and readable.

 ### Nested lists

  There is nothing hard about making a nested list. Just add a tab, or
  spaces for nested elements such as:

     - element 1
       - element 1.1
       - element 1.2
     - element 2
       - element 2.1
     - element 3

  For lists with * and ordered lists it works as well.

 ## THE CHALLENGE

  In the new file add a first-level heading with Lists as content.

  Try to write your own list. Please create a new file and create an
  unordered list in it:

   » One   » 1.1
           » 1.2

   » Two   » 2.1
           » 2.2

   » Three
   » Four
   » Five

   ## LINKS (Exercise 5 of 12)

  We often need to make a reference for something. There are two ways to
  create links: inline-style and reference-style.

  By the way, the easiest way to create a link is to just paste the link
  into a Markdown file. URLs and URLs in angle brackets will automatically
  get turned into links:

     http://www.example.com or <http://www.example.com>

  |> (http://www.example.com) or <http://www.example.com>

 ### Inline style

  Links in Markdown have this format:

     [text](href "alt")

  Above, text is text that will be a link, href is your reference to the
  resource (similar to href attribute in HTML), alt is an alternative text
  for link (similar to alt attribute in HTML). Text in a link may have any
  formatting, which means you are able to use emphasis in your links, if
  needed.

  Here are more real world examples:

     [Google](https://www.google.com)
     [Google Homepage](https://www.google.com "Google Homepage")

 ## Reference style

  Sometimes you have to use the same link in different places, so it would
  be convenient to use one reference for all of these links. So you may do
  this like so:

     [NodeSchool Site][ref]
     [GitHub][1]
     [Remark parser]

     Some text to show that the reference links can follow later:

     [ref]: http://www.nodeschool.io
     [1]: https://github.com/
     [Remark parser]: http://remark.js.org/

  As you may notice above, references are case-insensitive and you are free
  to use numbers for creating references or use link text itself as its
  reference.

 ## IMAGES (Exercise 6 of 12)

  The embedding of images is very similar to insertion of links. To embed an
  image you have to use this syntax:

     ![alt text](url)

  As you may see, the only difference is that you have to add an exclamation
  mark before squared brackets. alt text is an alternate text for an image
  (similar to alt attribute in HTML). url is the URL of an image (similar to
  src attribute in HTML).

  The reference style also works for images. You can do something like this:

     ![reference style][logo]

     [logo]: ./logo.png

 ## BLOCKQUOTES (Exercise 7 of 12)

  Sometimes we need to quote someone's words. In that case, blockquotes are
  exactly what we need.

  The syntax of blockquotes is simple:

     > This is my blockquote.
     > This line is part of the same quote.

  This will look like this:

   > This is my blockquote. This line is part of the same quote.

  As you have seen, the line-break doesn't break a block of quote. To
  separate a few quotes just add an empty line between them.

  You are able to put Markdown into a blockquote, therefore this will work
  as well:

     > **Markdown** is a _lightweight markup language_ with plain text formatting syntax designed so that it can be converted to **HTML** and many other formats.
     > - from [Wikipedia](https://en.wikipedia.org/wiki/Markdown)

 ## THE CHALLENGE

  Start the new file with Blockquotes as heading.

  Add a quote from William Shakespeare's play Hamlet:

   > To be, or not to be, that is the question.

  And add an original author to the quote right on the next line after this
  quote. When you are done, verify your solution.

  ## CODE (Exercise 8 of 12)

  Code is a part of Markdown spec. There are two ways to add code in your
  document: inline code and blocks of code.

 ### Inline code

  To mark a part of text as code, just wrap it in back-ticks (  ` ). Here is
  an example:

     Inline code transforms into `<code>` html-tag.

  |> Inline code transforms into <code> html-tag.

 ### Blocks of code

  Blocks of code are either fenced by lines with three back-ticks (   ```),
  or are indented with four spaces.

  Syntax highlighting isn't part Markdown's spec. However, many renderers
  support syntax highlighting. Which languages are supported and how those
  language names should be written will vary from renderer to renderer.

     ```js
     console.log('This is JavaScript syntax highlighting!');
     ```

     ```
     No language indicated, so no syntax highlighting.
     ```

         Block of code with indentation.

  These two blocks will be rendered like so:

     console.log('This is JavaScript syntax highlighting!');

     No language indicated, so no syntax highlighting.

     Block of code with indentation.

  We recommend to use the fenced code blocks instead of blocks with
  indentation, because they support syntax highlighting. 

## TABLES (Exercise 9 of 12)

  Tables are not a part of Markdown spec, but a lot of parsers support them.
  Especially GFM which are used on GitHub.

  The creation of tables in Markdown looks exactly like drawing using dashes
  (-) and pipes (|). Also, you may use colons to align columns. For example:

     | Head         | of       | Table         |
     | ------------ |:--------:| ------------ :|
     | left-aligned | centered | right-aligned |
     | left-aligned | centered | right-aligned |

  The table above will be rendered like this:

 Head            of    Table
 ------------ -------- -------------
 left-aligned centered right-aligned
 left-aligned centered right-aligned

  There are a few important things here:

   » There must be at least 3 dashes separating each header cell. Colons to                                                                     
     align columns count as dashes.
   » The outer pipes (|) are optional.
   » You can use inline Markdown in cells.

  That means you can do something like this:

     Markdown | Less | Pretty
     --- | --- | ---
     *Still* | `renders` | **nicely**

  It doesn't looks so nice, but it works as expected:

 Markdown Less    Pretty
 -------- ------- ------
 Still    renders nicely

 ## HORIZONTAL RULES (Exercise 10 of 12)

  Sometimes we have to divide some information. In HTML we use the <hr> tag,
  which means horizontal rule.

  There's nothing hard to make a horizontal rule in Markdown. Just type
  three or more dashes (-), asterisks (*) or underscores (_):

     Dashes

     ---

     Asterisks

     ***

     Underscores

     ___

  And it will turn into:

  Dashes

 ─────────────────────────────────────────────────────────────────────────────
  Asterisks

 ─────────────────────────────────────────────────────────────────────────────
  Underscores

 ─────────────────────────────────────────────────────────────────────────────
  As you may remember from the Headings exercise, three dashes on the next
  line makes a second-level heading. To avoid this behavior, just add an
  empty line between text and these dashes.

 ## HTML (Exercise 11 of 12)

  If you want to style something more than is allowed in Markdown, you can
  use raw HTML in your Markdown and it'll work pretty well.

     <p align="center">Centered text works well!</p>

  And you will get a centered paragraph.

  Sometimes it's helpful, but be careful! Markdown inside HTML won't be
  rendered! That means if you write something like this:

     <span>Markdown **won't** work here!</span>

  It won't work.

 ## GFM (Exercise 12 of 12)

  If you are a developer, then you have heard about GitHub. GitHub is an
  important part of the community. Why are we talking about it? That's
  because GitHub is a big customer of Markdown. Even more, GitHub uses its
  own version of the Markdown syntax that provides an additional set of
  useful features. This version of markdown is called GitHub Flavored
  Markdown or simply GFM.

  From previous exercises you are already familiar with syntax highlighting
  in blocks of code and tables. However, there are some other features which
  may be helpful for you.

 ### Task lists

  To create a task list you should create an ordered or unordered list. Then
  you can use squared brackets that will be turned into checkboxes. An x
  between them makes the item marked as completed. Example:

     - [x] [links](#), **formatting**, and <del>tags</del> supported
     - [x] list syntax required (any unordered or ordered list supported)
     - [x] this is a complete item
     - [ ] this is an incomplete item

   » [x] [links](#), formatting, and <del>tags</del> supported
   » [x] list syntax required (any unordered or ordered list supported)
   » [x] this is a complete item
   » [ ] this is an incomplete item

 ### SHA references

  Any reference to a commit’s SHA-1 hash will be automatically converted
  into a link to that commit on GitHub:

     4ad0c921206dec4d1518f4aeead932e7617f934f
     denysdovhan/how-to-markdowkn@4ad0c921206dec4d1518f4aeead932e7617f934f

 ### Issue and Pull request references

  Any number that refers to an Issue or Pull Request will be automatically
  converted into a link:

     #1
     denysdovhan/how-to-markdowkn#1

 ### Username @mentions

  Typing an @ symbol, followed by a username, will notify that person to
  come and view the comment. This is called a @mention, because you’re
  mentioning the individual. You can also mention @teams within an
  organization.

 ### Emoji

  It's a funny part, but it's still important. GFM also supports emoji!

  ✨ 🐫 💥

  To see a list of every emoji that is supported, check out the [Emoji Cheat
  Sheet](http://www.emoji-cheat-sheet.com/).  