<h1>Lasso Integrations</h1>

<p>There are several ways to integrate an online form with Lasso. The current and recommended method of integrating forms with Lasso is via the <b>Lasso API</b>.</p>

<h3><a name="using-api">Using the Lasso API</a></h3>

<p>The full API reference is available at <a href="https://platform.lassocrm.com/#/api" target="_blank">platform.lassocrm.com/#/api</a>. See <a href="https://github.com/eci-lasso/single-project-form/blob/master/lead.json">lead.json</a> for an example of a JSON submission.</p>

<p>The <a href="https://constructionsupport.ecisolutions.com/s/article/Lasso-Integrations-Lasso-API-and-Integrations" target="_blank">Lasso API and Integrations</a> help article contains instructions on accessing and using the API, and the <a href="https://constructionsupport.ecisolutions.com/s/article/Lasso-Project-Admin-Center-Manage-Website-Tracking-Website-Analytics" target="_blank">Add Website Tracking</a> help article contains instructions on setting up website tracking.</p>

<p>For WordPress forms, the plugin can be downloaded from <a href="https://github.com/eci-lasso/wp-plugin" target="_blank">wp-plugin</a> and set up as per the instructions in the <a href="https://constructionsupport.ecisolutions.com/s/article/Lasso-Integrations-Integrate-Online-Form-Registration-Page-with-Lasso" target="_blank">Integrate Online Form (Registration Page) with Lasso</a> help article.</p>

<p>Troubleshooting tips are available in the <a href="https://constructionsupport.ecisolutions.com/s/article/Lasso-FAQs-Online-Form-Registration-Page-Questions-Troubleshooting" target="_blank">Online Form (Registration Page) Questions/Troubleshooting</a> help article.</p>

<h3><a name="using-php">Using PHP</a></h3>

<p>If using the <b>LassoUID</b> instead of the <b>Lasso API Key</b> or if there is a need for multi-project submission form, PHP is the recommended method.</p>

<p>See <a href="https://github.com/eci-lasso/single-project-form" target="_blank">single-project-form</a> for a single-project submission example and <a href="https://github.com/eci-lasso/multi-project-form">multi-project-form</a> for a multi-project submission example.</p>

<p><b>DO NOT</b> edit the files in the <b>SRC</b> folder as this will impact the data being submitted to Lasso.</p>

<h3><a name="other-methods">Using Other Methods</a></h3>

<p>Simpler methods of creating submission forms are available as shown under <a href="https://github.com/eci-lasso/legacy-forms" target="_blank">legacy-forms</a>; however, these methods are not recommended as they are outdated and increase the chances of getting spam submissions</p>
