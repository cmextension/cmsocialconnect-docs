===================
Twitter integration
===================

To integrate with Twitter, you go to `https://apps.twitter.com/ <https://apps.twitter.com/>`_ to create an application.

Click "Create New App".

.. image:: ../images/twitter_config_1.jpg

Provide the required information. Ensure you also enter your site URL in Callback URL field, otherwise callback will be disabled and you will get error when connecting to Twitter.

.. image:: ../images/twitter_config_2.jpg

After your app is created, click "Keys and Access Tokens" tab to get API key and API secret.

.. image:: ../images/twitter_config_3.jpg

Consumer key (or API key), consumer secret (API key) are the values you need to enter in your Twitter Joomla! plugin.

.. image:: ../images/twitter_config_4.jpg

In your back-end, go to Extensions -> Plugin Manager, search for "CM Social Connect - Twitter integration" plugin.

.. image:: ../images/twitter_plugin_list.jpg

Edit the plugin, you set "Status" to "Enabled", enter the API key and API secret of your Twitter application.

.. image:: ../images/twitter_plugin_edit.jpg

Save the plugin. Go to your site's front-end, now you can see the Twitter icons in registration form, login form and login module.


Login form:

.. image:: ../images/twitter_config_login.jpg


Registration form:

.. image:: ../images/twitter_config_registration.jpg


Login module:

.. image:: ../images/twitter_config_module.jpg