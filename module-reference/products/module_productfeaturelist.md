<div class="description">
<h3 class="skiptoc">Description</h3>
<p>Displays using the <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/e-commerce/individual-product-small">Individual Product - Small</a> layout all the products tagged with a specified tag.</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_productfeaturelist,tag,rowLength,sortType,targetFrame,useBackupTemplate</span>}</p>
</div>
<div id="parameters">
<h3>Parameters</h3>
<ul>
    <li>tag being the product tag</li>
    <li>rowLength e.g. 3</li>
    <li>sortType can be alphabetical, price, date, expirydate or weight</li>
    <li>targetFrame - possible values are  _blank, _self and _top. This parameter is used to specify the frame you want the item to open in.</li>
    <li>useBackupTemplate can be true or false</li>
</ul>
</div>
<div id="layouts">
<h3>This module is rendered with these layouts</h3>
<p>
The {<span>module_productfeaturelist</span>} module is always rendered using either the <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/e-commerce/individual-product-small">Individual Product - Small</a> layout or the backup one. The site visitor is redirected to the product detail view (rendered using the <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/e-commerce/individual-product-large">Individual Product - Large</a> layout) only after clicking one of the links outputted by one of these tags: {<span>tag_button,Your Text</span>}, {<span>tag_name</span>} or {<span>tag_itemurl_withhost</span>}.
</p>
<ul>
    <li>Online Shop Layouts &gt; <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/e-commerce/individual-product-small">Individual Product - Small</a></li>
    <li>Online Shop Layouts &gt; Individual Product - Small {<span>Backup)</span></li>
    <li>This module also supports <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/custom-templates">custom templates</a></li>
</ul>
</div>
<div id="Examples">
<h3>Examples</h3>
<ul>
    <li>{<span>module_productfeaturelist,special offer</span>} - lists all the products that are tagged with the "special offer" tag</li>
    <li>{<span>module_productfeaturelist,special offer,,price,_blank,true</span>} - lists the products that are tagged with the "special offer" tag using the backup template. The products are sorted by price (cheapest first) and when clicking the product's name the detail view opens in a new window</li>
    <li>{<span>module_productfeaturelist,special offer,3,price,_blank,true template="/layouts/custom/productfeaturelist.tpl"</span>} - lists the products that are tagged with the "special offer" tag using a custom template (the "true" parameter that states the backup template should be used is ignored). The products are sorted by price (cheapest first) and when clicking the product's name the detail view opens in a new window</li>
</ul>
</div>