# swarm

Swarm initialized: current node (v10tztxpdx6gwj19xi1c7ajg1) is now a manager.

To add a worker to this swarm, run the following command:

    docker swarm join --token SWMTKN-1-2m5quml2v3fbvqccufgj07pyq5vuzi7zzmt1rwx2ye34fyp4vs-2dvuoodprs1exjzlwvuj0fsjn 172.31.47.145:2377

To add a manager to this swarm, run 'docker swarm join-token manager' and follow the instructions.

# secret mysql_root_password

$ printf "Y@ZG58@LZQzn" | docker secret create mysql_root_password -
kdpi6nk6lkq19q07k6odk6g6p

