# Flushing Web Template
This folder contains a template of the V9 custom CSS based on MDBootstrap.

<h2>Quick Reference</h2>

Start by specifying the document theme as a body attribute:
<pre>&lt;body class="europa"&gt;</pre>

Accent colours are then specified via element classes. For example:
<pre>&lt;div class="blue"&gt;
    &lt;p class="gold-text"&gt;Gold text over blue background&lt;/p&gt;
&lt;/div&gt;</pre>

This template will automatically use the official Flushing font faces, provided that the are either present in the client device or imported into the page along with the CSS:
<pre>&lt;link rel="stylesheet" media="screen" href="https://fontlibrary.org/face/selawik" type="text/css" /&gt;
&lt;link rel="stylesheet" media="screen" href="https://fontlibrary.org/face/muli" type="text/css" /&gt;</pre>

Once that is done, subtitles and emphasis are also available to use:
<pre>&lt;p class="subtitle"&gt;This paragraph has &lt;span class=emphasis green-text"&gt;emphasis&lt;/span&gt; inside.&lt;/p&gt;</pre>

For more details, and a documented overview, see the <kbd>Flushing.html</kbd> file.

<h2>Additional documentation</h2>
Apart from the specific colours, fonts and style choices of Flushing, the rest of MDBootstrap is available. Start with their own documentation to discover all avaiable functionality.
