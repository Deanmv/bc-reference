<div class="description">
<h3 class="skiptoc">Description</h3>
<p>This module will display the Facebook like button.</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_facebooklike, moduleTemplateGroup="", language="en_US", url="", layout="", showFaces="true", width="450", verb="like", font="", colorScheme=""</span>}</p>
</div>
<div id="parameters">
<h3>Parameters</h3>
<ul>
    <li>moduleTemplateGroup - This will specify a module template group, which is a folder located in FTP under <strong>/ModuleTemplates/SocialMedia/FacebookLike/</strong></li>
    <li>language &ndash; Can be any <a href="http://www.facebook.com/translations/FacebookLocales.xml">Facebook locales</a> ISO language and country codes combined by an underscore (e.g en_US). If the parameter is not present, this will default to en_US</li>
    <li>url &ndash;  If the parameter is not present, this will default to the current page URL. This must be a valid URL otherwise the Facebook plugin returns error when the button is pressed</li>
    <li>layout &ndash; standard, button_count, box_count. If the parameter is not present, the default value will be standard.</li>
    <li>show faces &ndash; true, false. If the parameter is not present, the default value will be true</li>
    <li>width &ndash; Any positive integers. If the parameter is not present, the default value will be 450</li>
    <li>verb &ndash; like, recommend. If the parameter is not present, the default value will be like</li>
    <li>font &ndash; 	arial, lucida grande, segoe ui, tahoma, trebuchet ms, verdana</li>
    <li>color scheme &ndash; light, dark. If the parameter is not present, the default value will be light</li>
</ul>
</div>
<div id="layouts">
<h3>This module is rendered with these layouts</h3>
<ul>
    <li>Module templates &gt; SocialMedia &gt; FacebookLike  &gt; Default  &gt; container.html </li>
    <li> See this article for activation steps: <a href="http://knowledgebase6.businesscatalyst.com/kb/crm-and-customer-related/social-media/facebook-like">Facebook Integration</a></li>
</ul>
</div>
<div id="Examples">
<h3>Examples</h3>
<ul>
    <li><span>{</span>module_facebooklike, url="<span>{</span>tag_itemurl_withhost<span>}</span>"} - this generates the Facebook Like button, using the full URL of the module item, for example http://mysite.com/module-url.</li>
    <li>Access this <a href="http://knowledgebase6.businesscatalyst.com/kb/crm-and-customer-related/social-media/facebook-like">article</a> for a complete reference</li>
</ul>
</div>