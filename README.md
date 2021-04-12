# Reading-Notes
What is Markdown?
Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.

You can use Markdown most places around GitHub:

1-Gists
2-Comments in Issues and Pull Requests
3-File with the .md or . markdown extension
- Syntax guide
Here’s an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files.

such as : 

Header / Emphasis / lists 1-unordered 2-ordered / images / links / Blockquotes / Inline code

- GitHub Flavored Markdown
GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features, many of which make it easier to work with content on GitHub.com.

Note that some features of GitHub Flavored Markdown are only available in the descriptions and comments of Issues and Pull Requests. These include @mentions as well as references to SHA-1 hashes, Issues, and Pull Requests. Task Lists are also available in Gist comments and in Gist Markdown files.

- Syntax highlighting
Here’s an example of how you can use syntax highlighting with GitHub Flavored Markdown

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
You can also simply indent your code by four spaces:

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
Here’s an example of Python code without syntax highlighting:

def foo():
    if not bar:
        return True
- Task Lists
If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests!
- Tables
You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |

- SHA references
Any reference to a commit’s SHA-1 hash will be automatically converted into a link to that commit on GitHub.

- Issue references within a repository
Any number that refers to an Issue or Pull Request will be automatically converted into a link.

- Username @mentions
You can also mention teams within an organization By placing a (@) before the name.

- Automatic linking for URLs
Any URL (like http:/www.any things.com) will be automatically converted into a clickable link.

- Strikethrough
Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

- Emoji
GitHub supports Emogi!

To see a list of every image we support, check out the Emogi  cheat sheet
