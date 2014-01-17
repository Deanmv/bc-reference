<div class="description">
<h3 class="skiptoc">Description</h3>
<p>Displays the list of blogs according to the blog list layout. Recommended use is to link directly to an individual blog rather than use the blog module. Use the Link Manager for Blog URL.</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_blog,filter,ID</span>}</p>
</div>
<div id="parameters">
<h3>Parameters</h3>
<ul>
    <li>filter - filtering criteria for display and can be one of the following:
    <ul>
        <li>i - individual item</li>
        <li>a - all items</li>
        <li>l - latest items</li>
        <li>r - random item</li>
        <li>cr - displays a random item in a particular category</li>
    </ul>
    </li>
    <li>ID - system generated (do not change)</li>
</ul>
</div>
<div id="layouts">
<h3>This module is rendered with these layouts</h3>
<ul>
    <li>Blog Layouts &gt;<a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/Blogs/blog-post-details-layout"> Post Details</a></li>
    <li>This module also supports <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/custom-templates">custom templates</a></li>
</ul>
</div>
<div id="Examples">
<h3>Examples</h3>
<ul>
    <li>
    {<span>module_blog,i,419</span>} - will display the individual blog with ID of 419.
    </li>
</ul>
</div>