$Id$

Views Send allow sending mass mailing using Views Bulk Operations. The messages
will be queued in a spool table and will be delivered only on cron. You can
control how many messages will be send per cron run.

Table of contents
=================

1. Installation
2. Configure
3. How it works?

1. Installation
===============

Proceed as with all modules in Drupal.

2. Configuration
================

General settings can be configured at: Site Configuration > Views Send

3. How it works?
================

1.1 Create a view and add at least one column containing E-mail addresses.
1.2 [Optional] Expose Views filters to let the user easily build list of recipients using UI.
1.3 Create a "Page" display and set the Style to "Bulk Operations".
1.4 On "Bulk Operations" Style configuration, under "Selected operations", select Send mass mail (views_send_mail_action).
1.5 Save the view, load the page, use exposed filters to build the list, select all or some rows and choose "Send mass mail".
1.6 Fill the message form to configure the E-mail. Use tokens to personalize your E-mail.
1.7 Preview and send the message.

Module developer & maintainer

Claudiu Cristea (aka claudiu.cristea)
http://drupal.org/user/56348
