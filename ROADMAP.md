# Roadmap

### Pre-Release

_(these are done, will be considered part of 1.0 on release)_

-   [x] Docker install script
-   [x] Docker app templates
-   [x] Config file stores selected apps
-   [x] Allow app.override.yml files to be used
-   [x] Consider alternative handling of `hostname` (maybe subfolder?) to avoid using `-f` in `docker-compose up -d`
-   [x] Top 10+ LSIO containers (excluding deprecated)
-   [x] Improve install script
-   -   [x] Run apt update/upgrade
-   -   [x] Run as root

### 1.0

_(this is the active to-do list, not specifically in any order)_

-   [ ] Handle multiple architectures
-   [ ] Menu to make selection easy
-   -   [ ] Prompt to fill in environment variables
-   -   -   [ ] Prompt to set timezone
-   -   -   [ ] Prompt to set user and group
-   -   -   [ ] Prompt to set folder locations
-   -   -   [ ] Set permissions on folders/files (755/644)
-   -   -   [ ] Set ownership on folders/files (user:group)
-   -   -   [ ] Check for apps using the same port
-   -   [ ] Prompt to select desired apps
-   -   -   [ ] Prompt to run `docker-compose up -d` (making it optional)
-   -   [ ] Prompt to enable/disable reverse proxy per app in letsencrypt config
-   -   [ ] Possibly prompt to select which apps should be configured to use a VPN (depending on how we end up handling VPN)
-   [ ] More app templates
-   -   [ ] Include at least one VPN option (and adjust other apps to work through VPN)
-   [ ] Include additional configs for letsencrypt container (or PR to their repo for inclusion)
-   [ ] Documentation
-   -   [ ] Formally address project goals/mentality
-   -   [ ] Explain how to get started
-   -   [ ] Explain how to change app selections after setup
-   -   [ ] Explain how to change environment variables after setup
-   -   [ ] Explain how to make adjustments to all files manually without using the menus
-   -   [ ] Explain why/how `hostname` is used
-   -   [ ] Credits
-   -   [ ] Contribution guidelines
-   -   [ ] License
-   [ ] Testing
-   -   [ ] Travis
-   -   [ ] Shellcheck

### 1.1

_(these are plans for the future)_

-   [ ] [???](http://knowyourmeme.com/memes/profit)
-   [ ] [Profit](http://knowyourmeme.com/memes/profit)
