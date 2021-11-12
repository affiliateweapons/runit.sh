# runit.sh
Install apps from the command line with one liners.

# How to use
Use the easy to remember commands below.

# Available apps
## Portainer
```
bash <(curl -sSv https://runit.sh/docker)
```
## Portainer
```
bash <(curl -sSv https://runit.sh/portainer)
```
## Pi-Hole
```
bash <(curl -sSv https://runit.sh/pihole)
````  
## Brave
```
bash <(curl -sSv https://runit.sh/brave)
````  

# CURL options
If you want less verbosity and 1 character less to typeand remember you can use
```
curl -sS
```
You can also pipe to sh
```
curl https://runit.sh/docker | sh
```

# Bundles
There are bundles you can run that basically chains multiple apps all at once including their dependencies.

## pihole
```
  bash <(curl -sSv https://runit.sh/pihole)
````  