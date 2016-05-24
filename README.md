Get the Github project in your workspace
> git clone https://github.com/debdayal/mongodb-docker.git

If you want to build your own docker image and upload to your docker hub account, then do the following

> cd mongodb-docker

> docker build --force-rm -t your-name/mongodb

> docker login 

> docker push your-name/mongodb

> docker pull your-name/maongodb

> docker run -p 27017:27017 --name mongodb -d your-name/mongodb

But if you want to just run mongodb then you can pull from my docker hub account 

> docker run -p 27017:27017 --name mongodb -d debdayal/mongodb

If your Vagrant Ubuntu VM has a private IP, say, 192.168.33.10 then from your Windows machine you can connect to MongoDB instance using any MongoDB client Robomongo or MongoChef

Follow tutorial:
https://docs.docker.com/engine/examples/mongodb/

