# Intro
Tutorial Lab: Penetration testing – Attacks
# Dependencies
- docker
- docker-compose
# Deployment
- git clone
- docker-compose build --no-cache
- docker-compose up -d 
# Content

There are six containers in this project.
- **www** - Apache, PHP, Mutillidae source code
- **database** - The MySQL database
- **database_admin** - The PHPMyAdmin console
- **ldap** - The OpenLDAP directory
- **ldap_admin** - The PHPLDAPAdmin console
- **investigator** - Kali Linux container
