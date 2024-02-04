## Private docker repository with authorization
### 1. Install
1. `cd auth && htpasswd -Bc registry.password username && cd -`
2. `docker compose up -d`
3. Configure nginx. Default configuration is in ./config folder.
