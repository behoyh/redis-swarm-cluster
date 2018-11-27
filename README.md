# redis-swarm-cluster

## You should have a Docker Swarm setup already.

run `docker stack deploy -c redis-compose-stack.yml <name>`

Place folders `redis/` and `redis-slave/` in the root directory for all of your *Workers* and *Managers* that will be running an instance of this app. 

That's it!
