# minidock
So this is docker with multi-sites on nginx, phpmyadmin, mysql, redis
you can start all the containers by running 'startmeup'
when you look in 'minidock' there's all the docker files (docker-compose.yml most important
the ```logs```, ```projects``` and ```sites``` directories are outside the ```minidock``` directory, so you can store them somewhere else
first copy env-example to .env and edit the variables
then either run ```startmeup``` or docker-compose up -d and it will build the images for you

Thanks to laradock for the inspiration
