<div class="description">
<h3 class="skiptoc">Description</h3>
<p>Displays the list of Web App Items submitted by a customer (must be logged in).</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_webappscustomer,ID,filter,itemID,,target,bkp,resultsPerPage,hideEmptyMessage,rowLength</span>}</p>
</div>
<div id="parameters">
<h3>Parameters</h3>
<ul>
    <li>ID - system generated web app id (do not change)</li>
    <li>filter - filtering criteria for display and can be one of the following:
    <ul>
        <li>i - individual item</li>
        <li>a - all items</li>
        <li>l - latest items</li>
        <li>r - random item</li>
        <li>cl - latest items in a particular category</li>
        <li>cr - displays a random item in a particular category</li>
    </ul>
    </li>
    <li>itemID - system generated individual item id (do not change)</li>
    <li>target - e.g. _blank. Specify the frame you want the item to open in</li>
    <li>bkp- specify True if you want to use the backup list template or leave empty</li>
    <li>resultsPerPage - total number of items per page before pagination is used (limit of 500 items per page)</li>
    <li>hideEmptyMessage - specify True if you don't want the No Items Found message to be displayed.</li>
    <li>rowLength - will limit the number of items per row when items are displayed as a list. Default is 1 item per row.</li>
</ul>
</div>
<div id="layouts">
<h3>This module is rendered with these layouts</h3>
<ul>
    <li>Web App Layouts &gt;&nbsp;<a href="/kb/modules-and-tags-reference/layouts/WebApps/webapp-list-layout ">List Layout </a></li>
    <li>This module also supports <a href="/kb/modules-and-tags-reference/layouts/custom-templates">custom templates</a></li>
</ul>
</div>
<div id="Examples">
<h3>Examples</h3>
<ul>
    <li>{<span>module_webappscustomer,56,a,</span>} - will display all web app items that belong to the customer that's logged in for a web app with ID 56</li>
    <li>{<span>module_webappscustomer,56,c,14609,,_blank,,13 template="/layouts/custom/walist.html"</span>} - will display the webapp items in the category with the ID 14609 using the walist.html <a href="/kb/modules-and-tags-reference/layouts/custom-templates">custom template</a>, 13 items per page </li>
</ul>
</div>