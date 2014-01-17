<div class="description">
<h3 class="skiptoc">Description</h3>
<p>Displays a list of products (in a given catalog or all the products on the site). This module does not use a layout, its output is an unordered list.</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_productlistdump,catID,rowLength,targetFrame,sortBy</span>}</p>
</div>
<div id="parameters">
<h3>Parameters</h3>
<ul>
    <li>catID - the catalogID, the productlistdump will list the products inside that catalog. This can also be "-1" - this will list all the products in the site.</li>
    <li>rowLength - will limit the number of items per row when items are displayed as a list. Default is 1 item per row</li>
    <li>targetFrame - possible values are  _blank, _self and _top. This parameter is used to specify the frame you want the item to open in.</li>
    <li>sortBy - will sort the item in specified order
    <ul>
        <li>Alphabetical - sorts items alphabetically</li>
        <li>Weight - sorts items by weight</li>
    </ul>
    </li>
</ul>
</div>
<div id="layouts">
<h3>This module is not rendered using a layout.</h3>
<p>The list of catalogs is ordered as an unordered list:</p>
<p>&lt;ul class="catalouelistdump"&gt;</p>
<p>&lt;li&gt;&lt;a href="/catalog1/product1"&gt;This is my first product&lt;/a&gt;&lt;/li&gt;</p>
<p>&lt;li&gt;&lt;a href="/catalog1/product2"&gt;This is my secondproduct&lt;/a&gt;&lt;/li&gt;</p>
<p>&lt;/ul&gt;</p>
</div>
<div id="Examples">
<h3>Examples</h3>
<ul>
    <li>{<span>module_productlistdump,63858,,_blank,Alphabetical</span>} - displays all the products in the catalog with the ID 63858 ordered alphabetically. Clicking a product will open its detail view (rendered using the <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/e-commerce/individual-product-large">Individual Product - Large</a> layout) in a new tab.</li>
    <li>{<span>module_productlistdump,-1,,_self,weight</span>} - displays all the products regardless of the catalog they are in ordered by weight. Clicking a product will open its detail view (rendered using the <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/e-commerce/individual-product-large">Individual Product - Large</a> layout) in the same tab.</li>
</ul>
</div>