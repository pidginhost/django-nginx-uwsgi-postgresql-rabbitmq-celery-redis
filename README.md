# django-nginx-uwsgi-postgresql-rabbitmq-celery-redis
An example django project that is already configured to use django, nginx, uwsgi, postgresql, redis, rabbitmq, celery

## Required steps
1. Create an account on https://www.pidginhost.com/en/
2. Complete the 3 steps when deploying an app on the following link https://www.pidginhost.com/en/panel/apps/add:
    
    Step 1:
        Enter your project repo 

        https://github.com/pidginhost/django-nginx-uwsgi-postgresql-rabbitmq-celery-redis
    
    Step 2
        
        Enter the desired domain name which should point to the specified ip
    Step 3
    
        Select the desired applications, in this case (Postgresql, RabbitMQ, Redis)

    **Optional step but usefull, you should add your public ssh key if you want to ssh into the machine**
3. You can now point your browser to the domain and you will have a server deployed with ssl enabled and activated.

4. You can enable auto-update for the app once you make commits or pushes, using the notify URL and the secret provided for each application that you deploy.