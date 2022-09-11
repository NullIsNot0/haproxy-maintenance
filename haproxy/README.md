# HAProxy Maintenance
This example shows how to put HAProxy reverse proxied sites in maintenance mode using variables in global section.  
The code is to complement [https://medium.com/@edgars.voroboks/put-your-haproxy-site-in-maintenance-mode-315d132fc203](https://medium.com/@edgars.voroboks/put-your-haproxy-site-in-maintenance-mode-315d132fc203) article.

# Run example
Prerequisites: [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/install/) installed.
```bash
git clone https://github.com/NullIsNot0/haproxy-maintenance.git
cd haproxy-maintenance

# If you have Docker Compose version 1.x, run this:
docker-compose up
# If you have Docker Compose version 2.x, run this:
docker compose up
```
Open [http://localhost:3000](http://localhost:3000) for site01.  
Open [http://localhost:3001](http://localhost:3001) for site02.  
Open [http://localhost:4001](http://localhost:4001) for HAProxy stats page.  
