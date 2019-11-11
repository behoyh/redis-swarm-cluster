# redis-swarm-cluster

## You should have a Docker Swarm setup already.

Place folder `redis/` in the root directory for all of your nodes that will be running an instance of this container. 

run `docker stack deploy -c redis-compose-stack.yml <name>`

That's it!
