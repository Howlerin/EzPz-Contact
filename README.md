# === EzPz Contact ===
CONTRIBUTORS: Radu Vaduva
TAGS: email, contact, form, contact form, shortcode, sandbox, css, semantics, extensible xhtml, valid xhtml
REQUIRES AT LEAST: 2.5
TESTED UP TO: 2.6.1
STABLE TAG: 0.1b

EzPz Contact is a simple, highly extensible XHTML contact form featuring spam-reduction measures, GUI customization, and shortcode-based insertion.

== Description ==

Based partially on the classic [WP Contact Form](http://wordpress.org/extend/plugins/wp-contact-form/ "WP Contact Form for WordPress"), EzPz Contact includes newer WordPress features (e.g., shortcode) and greatly improved form security. EzPz Contact is just another contact form, except built with clean XHTML and improved security.

== Installation ==

This plugin is installed just like any other WordPress plugin.
Just upload the `/ezpz-contact/` folder and its contents to your plugins folder.

== Use ==

After activating this plugin, simply use the shortcode `[ezpz-contact]` wherever you want the EzPz Contact form. This shortcode takes no attributes.

`[ezpz-contact]`


You will also want to customize the EzPz Contact plugin from the *Settings > Contact* options menu. Here you can set the email address to receive submissions, text for legends, labels, and prompts, turn on spam reduction measure(s), etc.

Included with EzPz Contact is a example style sheet file with images. EzPz Contact features dynamic classes, so when an input field is returned to the user for an error-related issue, the input is given the class `error`, etc

The sample CSS includes some nice features, like styles for the default response messages and error input fields. You could just add the following to your current theme's style.css file:

`@import url('../../plugins/ezpz-contact/sample/econtact-basic.css');`

=====

You may have to adjust the the URL above to locate the `econtact-basic.css` file included with the plugin. But that's an easy way to see what the included style sheet does for you.
