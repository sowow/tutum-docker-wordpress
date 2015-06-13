tutum-docker-wordpress
======================

[![Deploy to Tutum](https://s.tutum.co/deploy-to-tutum.svg)](https://dashboard.tutum.co/stack/deploy/)

Out-of-the-box Wordpress docker image


Usage
-----

To create the image `sowow/wordpress`, execute the following command on the tutum-docker-wordpress folder:

	docker build -t sowow/wordpress .

You can now push your new image to the registry:

	docker push sowow/wordpress


Running your Wordpress docker image
-----------------------------------

Start your image:

	docker run -d -p 80:80 sowow/wordpress

Test your deployment:

	curl http://localhost/

You can now start configuring your Wordpress container!


More information
----------------

For details on how to access the bundled MySQL Server, set specific passwords or disable .htaccess,
please visit the [tutum/lamp repository on github](https://github.com/tutumcloud/tutum-docker-lamp)
