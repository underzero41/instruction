# Git Instruction

* git init- inicialization local repository programm
* git status- get information from git about current state
* git add info.md- adds tracking file "info.md"
* git add .- adds tracking of all files in a directory
* git commit -m "text"- commiting state of change
* git log-  output of all commits
* git checkout- moving from one commit to another
* git checkout master- moving to the current state of the file
* git diff- show differences between current file and fie with last commit 
# Symbol's instruction

* Header - select headings. The number of “#” characters sets the heading level (6 levels are supported).
* = or - – by underlining these characters (at least 3 in a row) headings of the first (“=”) and second (“-”) levels are highlighted.
* **Bolt** or __bolt__ (**/__ before and after)
* *Italic* or _Italic_ (*/_ before and after)
* ***Bold italic style*** (*** before and after)
* ~~Strikethrough text~~ (~~ before and after)
* String – unordered lists, character “*” at the beginning of the string 
* 1., 2., 3. ... - numbered lists
example:
1. First line
2. Second line
3. Third line

* > This is a blockquote. It is usually rendered indented and with a different background color.

# Note, tip, important, cauting, warning.

> [!NOTE]
> Information the user should notice even if skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]
> Essential information required for user success.

> [!CAUTION]
> Negative potential consequences of an action.

> [!WARNING]
> Dangerous certain consequences of an action.

# Angle brackets, Apostrophes and quotation marks

* If angle brackets are used in the text of the file (for example, to indicate a placeholder), they must be encoded manually. Otherwise, the Markdown markup treats them as HTML tags.

For example, script name <> should be encoded as &lt;script name&gt; or \<scriptname>. (symbols \ < >) and (&lt ;  and &gt ; without spaces)

Angle brackets do not need to be escaped in text formatted as inline code or in blocks of code.

If you copy text from Word into the Markdown editor, it may contain bookish (curved) apostrophes or quotation marks. They need to be replaced with code or regular apostrophes or quotation marks. Otherwise, unreadable text, such as Itâ€™s, may be displayed after the file is published.

The following are the encodings for these punctuation marks:

left (opening) quote: & # 8220;;
right (closing) quote: & # 8221;;
right closing single quote or apostrophe: & #8 217;;
left opening single quote (rarely used): & # 8216;.
> All symbols without spaces!

# Links usage
https://learn.microsoft.com/ru-ru/contribute/how-to-write-links

