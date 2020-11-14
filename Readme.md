# WP-SARAHSPELL

Enables Arabic Spell Checking in the TinyMCE editor.

## Description

Enables Arabic Spell Checking in the TinyMCE editor.
The plugin relies on our spell checking API server to check words and generate suggestions. For that a single API request is done, and the response will contain all the presumably misspelled words and their correction suggestions. The plugin also uses an API endpoint to check the validity of the API keys used for spell checking. No other info is sent or exchanged with the API.

This plugin relies on Classic Editor plugin (https://wordpress.org/plugins/classic-editor/) and must be installed before enabling this plugin.

Service website (In Arabic only): https://arabicspellchecker.com/
Service's Terms of use link (In Arabic only) : https://arabicspellchecker.com/terms.html

## Installation

Search for the plugin "wp-sarahspell" from the plugin page inside your WordPress dashboard, or to manually install it do the following:

1. Upload the folder (wp-sarahspell) to the plugins directory (wp-content/plugins).
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Clear your browser cache (This is important otherwise you will see the cached TinyMCE).
