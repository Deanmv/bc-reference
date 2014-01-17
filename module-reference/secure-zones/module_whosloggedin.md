<div class="description">
<h3 class="skiptoc">Description</h3>
<p>Displays the name of the contact that's currently logged in and it also displays the Log Out link. If the contact is not logged in the module will display "No one logged in. [Log in]"</p>
</div>
<div id="syntax">
<h3>Syntax</h3>
<p>{<span>module_whosloggedin,page</span>}</p>
</div>
<div id="parameters">
<h3>Parameters</h3>
<ul>
    <li>page - is the page you want to send the customer to when they click on [Log in] link.
    </li>
</ul>
</div>
<div id="Examples">
<h3>Examples</h3>
<p>{<span>module_whosloggedin,/loginpage.htm</span>}</p>
<ul>
    <li>when customer logged in - "John Smith logged in. <a href="/LogOutProcess.aspx">Log out</a>"</li>
    <li>when customer not logged in - "No one logged in. <a href="/loginpage.html">Log in</a>"</li>
</ul>
<p>{<span>module_whosloggedin</span>}</p>
<ul>
    <li>when customer logged in - "John Smith logged in. <a href="/LogOutProcess.aspx">Log out</a>"</li>
    <li>when customer not logged in - "No one logged in."</li>
</ul>
</div>