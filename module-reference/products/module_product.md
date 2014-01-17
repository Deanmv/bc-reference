<div class="description">
<h3 class="skiptoc">Description</h3>
<p>Displays an individual product from a given catalogue on a web page according to the <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/e-commerce/individual-product-small">Individual Product - Small</a> layout.</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_product,catID,prodID,targetFrame</span>}</p>
</div>
<div id="parameters">
<h3>Parameters</h3>
<ul>
    <li>catID - system generated catalogue id (do not change)</li>
    <li>prodID - system generated product id (do not change)</li>
    <li>targetFrame - possible values are  _blank, _self and _top. This parameter is used to specify the frame you want the item to open in.</li>
</ul>
</div>
<div id="layouts">
<h3>This module is rendered with these layouts</h3>
<p>
The {<span>module_product</span>} module is always rendered using either the <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/e-commerce/individual-product-small">Individual Product - Small</a> layout or the backup one. The site visitor is redirected to the product detail view (rendered using the <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/e-commerce/individual-product-large">Individual Product - Large</a> layout) only after clicking one of the links outputted by one of these tags: {<span>tag_button,Your Text</span>}, {<span>tag_name</span>} or {<span>tag_itemurl_withhost</span>}.
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
    <li>{<span>module_product,591,166845,_blank </span>} - will display a single product according to the <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/layouts/e-commerce/individual-product-small">Individual Product - Small</a>. If one clicks the product link the product detail window will open in a new tab.</li>
    <li>{<span>module_product,63882,5450055,_top template="/layouts/custom/productfeaturelist.tpl"</span>} - this rendes an individual product a custom template.</li>
</ul>
</div>