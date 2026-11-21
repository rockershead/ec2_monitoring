# ec2_monitoring

This project is a simple illustration on how to display important data about a ec2 node like cpu, memory,disk space used etc.

I am deploying them using simple docker compose files
I have combined the docker compose for grafana and prometheus because they are deployed on my local pc and I need these 2 containers to communicate between each other using url: http://prometheus:9090
