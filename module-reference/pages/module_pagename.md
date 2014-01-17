<div class="description">
<h3 class="skiptoc">Description</h3>
<p>This module simply renders a web page name.</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_pagename</span>}</p>
</div>
<div id="Examples">
<h3>Examples</h3>
<ul>
    <li>{<span>module_pagename</span>} - renders the name of the page in plain text</li>
    <li>The way to set up a different image which loads on a per page basis is to use the {module_pagename} to render the name of the page, but add this module to the image link, i.e. &lt;img src=&rdquo;/images/{module_pagename}.jpg&rdquo;&gt;.  This will then render the word &lsquo;About&rsquo; (if you are on a page named &lsquo;About&rsquo;) and the resulting image link would be &lt;img src=&rdquo;/images/About.jpg&rdquo;&gt;.</li>
</ul>
<ul>
    <li>You can also use this module between the title tags to set the title</li>
</ul>
</div>