<div class="description">
<h3 class="skiptoc">Description</h3>
<p>This module will display a Facebook Activity Feed.</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_facebookfeed, moduleTemplateGroup="", locale="en_US", url="{module_sitehost}", width="", height="", header="true", colorScheme="light", font="", borderColor="", recommendations="true"</span>}</p>
</div>
<div id="parameters">
<h3>Parameters</h3>
<ul>
    <li>moduleTemplateGroup - This will specify a module template group, which is a folder located in FTP under <strong>/ModuleTemplates/SocialMedia/FacebookFeed/</strong></li>
    <li>locale &ndash; Can be any <a href="http://www.facebook.com/translations/FacebookLocales.xml">Facebook locales</a> ISO language and country codes combined by an underscore (e.g en_US). If the parameter is not present, this will default to en_US</li>
    <li>url &ndash;  If the parameter is not present, this will use {module_sitehost} by default. This must be a valid URL otherwise the Facebook plugin returns error when the button is pressed</li>
    <li>width &ndash; Any positive integers. If the parameter is not present, the default value will be 300</li>
    <li>height &ndash; Any positive integers. If the parameter is not present, the default value will be 300</li>
    <li>header &ndash; true, false. If the parameter is not present, the default value will be true</li>
    <li>color scheme &ndash; light, dark. If the parameter is not present, the default value will be light</li>
    <li>font &ndash; arial, lucida grande, segoe ui, tahoma, trebuchet ms, verdana</li>
</ul>
</div>
<div id="layouts">
<h3>This module is rendered with these layouts</h3>
<ul>
    <li>Module templates &gt; SocialMedia &gt; FacebookComments  &gt; Default  &gt; container.html </li>
    <li>See this article for activation steps: <a href="http://knowledgebase6.businesscatalyst.com/kb/crm-and-customer-related/social-media/facebook-activity-feed">Facebook Integration</a></li>
</ul>
</div>
<div id="Examples">
<h3>Examples</h3>
<ul>
    <li>{<span>module_facebookfeed, moduleTemplateGroup="", locale="en_US", url="{module_sitehost}", width="", height="", header="true", colorScheme="light", font="", borderColor="", recommendations="true"</span>} - ?</li>
    <li>Refer to this <a href="http://knowledgebase6.businesscatalyst.com/kb/crm-and-customer-related/social-media/facebook-activity-feed">article</a> for a complete reference</li>
</ul>
</div>