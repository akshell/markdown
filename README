# Markdown Library

Tools for processing the
[Markdown](http://daringfireball.net/projects/markdown/) language.


## makeHTML()

To convert markdown text into HTML, use the `makeHTML()` function:

    use('markdown');
    ...
    var text = 'Markdown *rocks*.';
    var html = markdown.makeHTML(text);
   

## WMD

The [Wysiwym Markdown Editor](http://wmd-editor.com/) is a simple,
lightweight HTML editor for blog comments, forum posts, and basic
content management.

To install the editor, include `wmd.js` right before your closing
`<body>` tag:

    <script type="text/javascript"
            src="http://static.akshell.com/code/release/markdown/wmd/wmd.js">
    </script>

By default, WMD will turn the first textarea on your page into an
editor. You can modify this behavior with the `wmd-ignore` class,
described below.


### Adding Live Preview

Paste this code wherever you want your live preview to appear:

    <div class="wmd-preview"></div>

You can mix "wmd-preview" with your own class names to make applying
CSS easier.

Example:

    <div class="myClass <span class="highlight">wmd-preview</span>" id="myId"></div>


### Special Class Names

You can use the following class names to control WMD's auto-start
behavior:

`wmd-ignore` - Add to a textarea to prevent WMD from turning it into
an editor.

`wmd-preview` - Add to a div to turn show a live preview.

`wmd-output` - Add to a textarea or div to turn show the HTML output.
