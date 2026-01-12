# Ldap configuration (For now you have to configure it yourself)
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

