xnlang
======

学习<!DOCTYPE html>
<html>

    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
        <title>GETTING STARTED WITH BRACKETS</title>
        <meta name="description" content="An interactive getting started guide for Brackets.">
        <link rel="stylesheet" href="main.css">
    </head>
    <body>

<h1>GETTING STARTED WITH BRACKETS</h1>
<h2>This is your guide!</h2>

<!--
    MADE WITH <3 AND JAVASCRIPT
-->

<p>
    Welcome to a super early preview of Brackets, a new open-source editor for the next generation of
    the web. We’re big fans of standards and want to build better tooling for JavaScript, HTML and CSS 
    and related open web technologies. This is our humble beginning.
</p>

<!--
    WHAT IS BRACKETS?
-->
<p>
    <em>You are looking at an early build of Brackets.</em>
    In many ways, Brackets is a different type of editor. One notable difference is that this editor
    is written in JavaScript. So while Brackets might not be ready for your day-to-day use quite yet,
    we are using it every day to build Brackets.
</p>


<h2>We're trying out a few new things</h2>

<!--
    THE RELATIONSHIP BETWEEN HTML, CSS AND JAVASCRIPT
-->
<h3>Quick Edit for CSS and JavaScript</h3>
<p>
    When editing HTML, use the <kbd>Cmd/Ctrl + E</kbd> shortcut to open a quick inline editor that
    displays all the related CSS. Make a tweak to your CSS, hit <kbd>ESC</kbd> and you’re back to
    editing HTML. Or just leave the CSS rules open and they’ll become part of your HTML editor.
    If you hit <kbd>ESC</kbd> outside of a quick editor, they’ll all collapse. No more switching between
    documents and losing your context.
</p>

<samp>
    Want to see it in action? Place your cursor on the <!-- <samp> --> tag above and press
    <kbd>Cmd/Ctrl + E</kbd>. You should see a CSS quick editor appear above. On the right you will see
    a list of the CSS rules that are related to this tag. Simply scroll the rules with 
    <kbd>Alt + Up/Down</kbd> to find the one you want to edit.
</samp>

<a href="screenshots/brackets-quick-edit.png">
    <img alt="A screenshot showing CSS Quick Edit" src="screenshots/brackets-quick-edit.png" />
</a>

<!--
    LIVE PREVIEW
-->
<h3>Preview CSS changes live in the browser</h3>
<p>
    You know that "save/reload dance" we've been doing for years? The one where you make changes in
    your editor, hit save, switch to the browser and then refresh to finally see the result?
    With Brackets, you don't have to do that dance.
</p>
<p>
    Brackets will open a <em>live connection</em> to your local browser and push CSS updates as you
    type! You might already be doing something like this today with browser-based tools, but with Brackets
    there is no need to copy and paste the final CSS back into the editor. Your code runs in the
    browser, but lives in your editor!
</p>

<samp>
    If you have Google Chrome installed, you can try this out yourself. Click on the lightning bolt 
    icon in the top right or hit <kbd>Cmd/Ctrl + Alt + P</kbd>. When Live Preview is enabled on 
    an HTML document, all linked CSS documents can be edited in real-time. The icon will change from 
    gray to gold when Brackets establishes a connection to your browser.
    
    Now, place your cursor on the <!-- <img> --> tag above and use <kbd>Cmd/Ctrl + E</kbd> to open up the
    defined CSS rules. Try changing the size of the border from 1px to 10px or change the background
    color from "dimgray" to "hotpink". If you have Brackets and your browser running side-by-side, you
    will see your changes instantly reflected in your browser. Cool, right?
</samp>
        
<p class="note">
    Today, Brackets only supports Live Preview for CSS. We are currently working on Live Preview support
    for HTML and JavaScript. In the current version, you won't see changes to your HTML file until you save
    the document. Live previews are only possible with Google Chrome. We want to bring this functionality
    to all major browsers, and we're looking forward to working with those vendors.
</p>

<!--
    LET US KNOW WHAT YOU THINK
-->
<h2>Get Involved</h2>
<p>
    Brackets is an open-source project. Web developers from around the world are contributing to build 
    a better code editor. Let us know what you think, share your ideas or contribute directly to the 
    project.
</p>
<ul>
    <li><a href="http://brackets.io">Brackets.io</a></li>
    <li><a href="http://blog.brackets.io">Brackets Team Blog</a></li>
    <li><a href="http://github.com/adobe/brackets">Brackets on GitHub</a></li>
    <li><a href="http://github.com/adobe/brackets/wiki">Brackets Wiki</a></li>
    <li><a href="http://groups.google.com/group/brackets-dev">Brackets Developer Mailing List</a></li>
    <li><a href="https://twitter.com/#!/brackets">@Brackets on Twitter</a></li>
    <li>Chat with Brackets developers on IRC in #brackets on Freenode</li>
</ul>

    </body>
</html>
<!--

    [[[[[[[[[[[[[[[     ]]]]]]]]]]]]]]]
    [::::::::::::::     ::::::::::::::]
    [::::::::::::::     ::::::::::::::]
    [::::::[[[[[[[:     :]]]]]]]::::::]
    [:::::[                     ]:::::]
    [:::::[                     ]:::::]
    [:::::[                     ]:::::]
    [:::::[                     ]:::::]
    [:::::[    CODE THE WEB     ]:::::]
    [:::::[  http://brackets.io ]:::::]
    [:::::[                     ]:::::]
    [:::::[                     ]:::::]
    [:::::[                     ]:::::]
    [:::::[                     ]:::::]
    [::::::[[[[[[[:     :]]]]]]]::::::]
    [::::::::::::::     ::::::::::::::]
    [::::::::::::::     ::::::::::::::]
    [[[[[[[[[[[[[[[     ]]]]]]]]]]]]]]]

-->
