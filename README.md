# adguard-tor-docker

## Usage
Edit and then copy the configuration files `AdGuardHome.yaml` and `dnscrypt-proxy.toml` into the `config` folder.  
To generate a BCrypt password for AdGuardHome, follow <https://github.com/AdguardTeam/AdGuardHome/wiki/Configuration#reset-web-password>  
Run `docker-compose up -d`.  
DNS available at 127.0.0.1:53 and AdGuardHome WebUI at 127.0.0.1:3000.
