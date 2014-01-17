<div class="description">
<h3 class="skiptoc">Description</h3>
<p>Displays a list of forums.</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_forum,filter,ID,targetFrame</span>}</p>
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
    <li>targetFrame - the frame in which to open the item in</li>
</ul>
</div>
<div id="layouts">
<h3>This module is rendered with these layouts</h3>
<ul>
    <li>Forum Layouts &gt; <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/Forums/individual-forum-layout">Individual Forum Layout</a></li>
    <li>This module also supports <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/custom-templates">custom templates</a></li>
</ul>
</div>
<div id="Examples">
<h3>Examples</h3>
<ul>
    <li>{<span>module_forum,i,317,true</span>} - it will display an individual forum with an id of 317 and it will display it in the new frame</li>
    <li>{<span>module_forum,a, template="/layouts/custom/individual_forum.tpl"</span>} - it will display all the forums on the site using the individual_forum.tpl <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/custom-templates">custom template</a></li>
</ul>
</div>