<div class="description">
<h3 class="skiptoc">Description</h3>
<p>When inserted into a page it will display the literature item(s). After adding the Literature module to a web page, you can make changes to it to slightly to alter its behavior.
</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_literature,filter,id,targetFrame</span>}</p>
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
    <li>id system generated (do not change)</li>
    <li>targetFrame the frame in which to open the item in</li>
</ul>
</div>
<div id="layouts">
<h3>This module is rendered with these layouts</h3>
<ul>
    <li>Media downloads <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/Media-Downloads/media-downloads-list-layout">List Layout</a></li>
    <li>This module also supports <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/custom-templates">custom templates</a></li>
</ul>
</div>
<div id="Examples">
<h3>Examples</h3>
<ul>
    <li>{<span>module_literature,i,823,_blank</span>} - This will display the link to individual literature item which when clicked will open in the new window</li>
    <li>{<span>module_literature,a,,_blank</span>} - This module will display links to all literature items which when clicked will open in the new window</li>
    <li>{<span>module_literature,l,</span>} - This module will display the latest items (default is 10 items)</li>
    <li>{<span>module_literature,r,</span>} - This module will display 1 random literature item</li>
    <li>{<span>module_literature,cr,14606,</span>} - This module will display 1 random literature item, from the category called "Company", identified through id 14606</li>
</ul>
</div>