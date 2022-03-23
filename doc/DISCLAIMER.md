# Ldap configuration (For now you have to configure it youeself)
Enable ldap Extension<br>
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

# LASTEST UPDATE REQUIRE MANUAL FIX WITH PHPMYADMIN

1. Run phpmyadmin after applying the update

2. Select 'joomla' database in the left panel

![step 1](dbprefix/fix1.jpg)

3. Select all tables in the right panel

![step 2](dbprefix/fix2.jpg)

4. Clic on the action menu

![step 3](dbprefix/fix2.5.jpg)

5. Clic add prefix to table

![step 4](dbprefix/fix3.jpg)

6. Enter the database prefix you see in the error message of joomla :
```
Table 'joomla.JuzW_menu' doesn't exist
```
it looks like 'JuzW_' in the prefix box and validate

![step 5](dbprefix/fix4.jpg)

7. You're done, all tables are prefixed with your prefix

![step 6](dbprefix/fix5.jpg)

