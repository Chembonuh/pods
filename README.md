# pods
# kubectl exec -it mariadb-6c658cf887-9h5xg -- /bin/bash
# mysql -u root -pjohn
# MariaDB [(none)]> GRANT ALL PRIVILEGES ON bitnami_wordpress.* TO 'bn_wordpress'@'%';
# FLUSH PRIVILEGES;
# FLUSH PRIVILEGES;
#
 oc cp wp-config.php wordpress-77b96bc968-6lq77:/bitnami/wordpress/wp-config.php
