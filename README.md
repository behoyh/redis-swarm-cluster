# redis-swarm-cluster

## You should have a Docker Swarm setup already.

Place folder `redis/` in the root directory for all of your **Windows** Workers and Managers that will be running an instance of this app. 

run `docker stack deploy -c redis-compose-stack.yml <name>`

That's it!
