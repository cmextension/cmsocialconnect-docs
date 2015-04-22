===================
Google+ integration
===================

To support Google login, you need to have a Google Developers project.

Go to `https://console.developers.google.com/ <https://console.developers.google.com/>`_, click "Create Project" button to create a new project.

.. image:: ../images/googleplus_config_1.jpg

Give your project a name.

.. image:: ../images/googleplus_config_2.jpg

After your project is created, on the left menu you go to APIs & auth -> Credentials, click "Create new Client ID button".

.. image:: ../images/googleplus_config_3.jpg

Select "Web application" as "Application type".

.. image:: ../images/googleplus_config_4.jpg

Select an email address and enter product name.

.. image:: ../images/googleplus_config_5.jpg

Enter your site URL in "Authorized JavaScript origins" option. For "Authorized redirects URIs" option you need to enter 3 URLs::

	http://yoursite.com/index.php?option=com_cmsocialconnect&task=registration.socialRegister&network=googleplus
	http://yoursite.com/index.php?option=com_cmsocialconnect&task=login.socialLogin&network=googleplus
	http://yoursite.com/index.php?option=com_cmsocialconnect&task=connect.socialConnect&network=googleplus

.. image:: ../images/googleplus_config_6.jpg

Click "Create Client ID", you can find your client ID and client secret in APIs & auth -> Credentials.

In your back-end, go to Extensions -> Plugin Manager, search for "CM Social Connect - Google+ integration" plugin.

.. image:: ../images/googleplus_plugin_list.jpg

Edit the plugin, you set "Status" to "Enabled", enter the client ID and client secret of your project.

.. image:: ../images/googleplus_plugin_edit.jpg

Save the plugin. Go to your site's front-end, now you can see the Google+ icons in registration form, login form and login module.


Login form:

.. image:: ../images/googleplus_config_login.jpg


Registration form:

.. image:: ../images/googleplus_config_registration.jpg


Login module:

.. image:: ../images/googleplus_config_module.jpg