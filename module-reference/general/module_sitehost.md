<div class="description">
<h3 class="skiptoc">Description</h3>
<p>Displays the host section of the URL.</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_siteurl</span>}</p>
</div>
<div id="Examples">
<h3>Examples</h3>
<ul>
    <li>{<span>module_sitehost</span>} - if this module is used on the URL of http://mysite.com/_blog/my_blog then this module will output http://mysite.com.</li>
</ul>
<p>
If this module is used on a secure URL, then the module will output the host of the non-secure URL the user navigated from. For example, if this module is used on https://mysite.worldsecuresystems.com and the customer navigated to this URL from http://mysite.com then this module will output http://mysite.com.
If the user started on the secure URL (i.e did not navigate from a non-secure URL of the site), then this module will use the default domain name of the site.
</p>
</div>