# docker-compose-rails-skel
This project is a skeleton for a rails app following ["Quickstart: Compose and Rails"](https://docs.docker.com/compose/rails/)

From this sketch you can run the following commands to jump-start your app:
```
docker-compose run web rails new . --force --no-deps --database=postgresql
sudo chown -R $USER:$USER . # Linux only
docker-compose build
```
Now you should continue from ["Connect the database"](https://docs.docker.com/compose/rails/#connect-the-database) section of the tutorial
