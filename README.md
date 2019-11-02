# homer-webapp
Homer5 Docker WebApp

Some customizations to the homer-webapp container

* skip the home dashboard page and jump straight to search page
* increase the height of the DB Nodes list box
* use the MySQL Native Driver (mysqlnd)
* enforce a MySQL timeout with mysqlnd so that the nginx auth-proxy doesn't timeout
