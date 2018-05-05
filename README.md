# Joomla_ynh
[![Install Joomla with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=joomla)

Joomla! is an award-winning content management system https://www.joomla.org/ <br> <strong>Version:</strong> 3.8.7 <br><br>

<h2>Why Joomla?</h2>
<p>Hundreds of developers have been improving Joomla! since the first version was released in 2005. This immense effort has made Joomla! very popular, easy to use, stable and secure. <strong>See for more details:</strong>https://www.joomla.org/3/</p><br>

<b>Note:</b>There is installer.php added for bypassing the web installation process. see https://github.com/joomla/joomla-cms/pull/2764

# Ldap configuration (For now you have to configure it youeself)
Enable ldap plugin<br>
Enter the following feilds:<br>
**Host:** localhost<br>
**Port**:389<br>
**LdapV3:** Yes<br>
**Authorisation Method:** Bind and search<br>
**Base DN:** dc=yunohost,dc=org<br>
**uid:** uid=[search]<br>
**User's DN:** ou=users,dc=yunohost,dc=org<br>
**Map Full Name:** displayname<br>
**Map Email:** mail<br>
**Map User ID:** uid<br>

# To-do
- [X] Installation and remove script.
- [ ] Ldap integration.
- [ ] Make update script better for updation from sources.
- [X] Backup and restore script.
- [ ] Add php-fpm.ini and php-fpm.conf(for the red error message in admin panel).
