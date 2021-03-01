# Postgres server
postgres_server is a postgresql server that store [flask_backend](https://github.com/BorodaUA/flask_backend) and [hacker_news_parser](https://github.com/BorodaUA/hacker_news_parser) data, as part of the [webportal](https://github.com/BorodaUA/webportal) project.


## How to use:
### Local development mode:
1. Clone the repo
2. Create .env file inside the repo with following data:
    - POSTGRES_USER=your postgres username
    - POSTGRES_PASSWORD=your postgres password
    - POSTGRES_DB=postgres default database name