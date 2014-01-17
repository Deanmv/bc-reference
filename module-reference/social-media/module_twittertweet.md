<div class="description">
<h3 class="skiptoc">Description</h3>
<p>This module will display a Twitter Tweet button.</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_twittertweet, moduleTemplateGroup="", language="en", url="", count="horizontal", text="", via="", related="", countUrl=""</span>}</p>
</div>
<div id="parameters">
<h3>Parameters</h3>
<ul>
    <li>moduleTemplateGroup - This will specify a module template group, which is a folder located in FTP under <strong>/ModuleTemplates/SocialMedia/TwitterTweet/</strong></li>
    <li>language &ndash; en, fr, de, it, es, ko, ja</li>
    <li>url &ndash;  if the parameter is not present, this will default to the current page URL. This must be a valid</li>
    <li>count &ndash; horizontal, vertical, none. If the parameter is not present, the default value will be horizontal</li>
    <li>text &ndash; this can have any text value. If the parameter is not present, this will default to the title of the page the button is on</li>
    <li>via &ndash; this should be a valid Twitter username</li>
    <li>related &ndash; this should be a valid Twitter username</li>
    <li>counturl &ndash; must be a valid URL</li>
</ul>
</div>
<div id="layouts">
<h3>This module is rendered with these layouts</h3>
<ul>
    <li>Module templates &gt; SocialMedia &gt; TweeterTweet &gt; Default  &gt; container.html </li>
    <li> See this article for activation steps: <a href="http://kb.worldsecuresystems.com/kb/add-social-media.html#main_Adding_a_Twitter_Tweet_button_to_your_site">Tweeter Integration</a></li>
</ul>
</div>
<div id="Examples">
<h3>Examples</h3>
<ul>
    <li><span>{</span>module_twittertweet, url="<span>{</span>tag_itemurl_withhost<span>}</span>"<span>}</span> - This will generate the Tweeter Tweet button, using the full URL of the module item, for example http://mysite.com/module-url.</li>
</ul>
</div>