<div class="description">
<h3 class="skiptoc">Description</h3>
<p>Displays a single dynamic menu when placed on the page or a template. menuID is the ID of the particular dynamic menu and should not be changed. The ID is set by module manager when menu is inserted into the page.</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_menu,menuID</span>}</p>
</div>
<div id="parameters">
<h3>Parameters</h3>
<ul>
    <li>menuID - system generated menu id (do not change)</li>
</ul>
</div>
<div id="layouts">
<h3>This module is rendered with these layouts</h3>
<ul>
    <li>The module is not rendered with a specific layout, it can be customized using either of the 2 methods below::
    <ul>
        <li>Site Manager &gt; Menus &gt; *YOURMENU* &gt; Menu look / Items look (see this <a href="http://kb.worldsecuresystems.com/kb/creating-dynamic-menu-using-default.html">article</a> for future reference)</li>
        <li>Your own css styles applied to the <a href="/kb_resources/screenshots/module_menu_std.png">classes and ids generated for the module</a></li>
    </ul>
    </li>
</ul>
<br />
<p>Enhanced usability and functionality is provided by <a href="http://knowledgebase6.businesscatalyst.com/kb/modules-and-tags-reference/modules/site-modules/Menus/module_menu-v2">module_menu v2</a>, which we strongly recommend using </p>
</div>
<div id="Examples">
<h3>Examples</h3>
<ul>
    <li>{<span>module_menu,128392</span>} - will generate the menu with the ID 128392</li>
</ul>
</div>