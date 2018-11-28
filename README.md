MantisBT-Teams
==============

A [MantisBT](http://www.mantisbt.org/) plugin to send bug updates to [Microsoft Teams].
Forked from [MantisBT-Slack](https://github.com/infojunkie/MantisBT-Slack) by infojunkie


# Setup
* Requires Mantis 2.0.x
* Extract this repo to your *Mantis folder/plugins/Teams*.
* On the MS Teams side, add a new "Incoming Webhooks" integration on the wanted channel and note the URL that Teams generates for you.
* On the MantisBT side, access the plugin's configuration page and fill in your Teams webhook URL.
* You can specify which bug fields appear in the Teams notifications. Edit the *plugin_Slack_columns* configuration option for this purpose.  Follow the instructions on the plugin configuration page.
