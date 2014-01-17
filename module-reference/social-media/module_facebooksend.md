<div class="description">
<h3 class="skiptoc">Description</h3>
<p>This module will display a Facebook Send button.</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_facebooksend, moduleTemplateGroup="", locale="en_US", url="", font="", colorScheme="light"</span>}</p>
</div>
<div id="parameters">
<h3>Parameters</h3>
<ul>
    <li>moduleTemplateGroup - This will specify a module template group, which is a folder located in FTP under <strong>/ModuleTemplates/SocialMedia/FacebookSend/</strong></li>
    <li>locale &ndash; Can be any <a href="http://www.facebook.com/translations/FacebookLocales.xml">Facebook locales</a> ISO language and country codes combined by an underscore (e.g en_US). If the parameter is not present, this will default to en_US</li>
    <li>url &ndash;  If the parameter is not present, this will default to the current page URL. This must be a valid URL otherwise the Facebook plugin returns error when the button is pressed</li>
    <li>color scheme &ndash; light, dark. If the parameter is not present, the default value will be light</li>
    <li>font &ndash; arial, lucida grande, segoe ui, tahoma, trebuchet ms, verdana</li>
</ul>
</div>
<div id="layouts">
<h3>This module is rendered with these layouts</h3>
<ul>
    <li>Module templates &gt; SocialMedia &gt; FacebookSend  &gt; Default  &gt; container.html </li>
    <li>See this article for activation steps: <a href="http://knowledgebase6.businesscatalyst.com/kb/crm-and-customer-related/social-media/facebook-send">Facebook Integration</a></li>
</ul>
</div>
<div id="Examples">
<h3>Examples</h3>
<ul>
    <li>{<span>module_facebooksend, moduleTemplateGroup="", locale="en_US", url="", font="", colorScheme="light"</span>}- will display a content of a single catalogue according to the Individual Catalogue Layout inside a new window</li>
</ul>
</div>