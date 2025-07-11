# Info anzeigen
docker run --rm -v ./ldproxy:/src ghcr.io/ldproxy/xtracfg:4.2.1 info

# Version anzeigen
docker run --rm -v ./ldproxy:/src ghcr.io/ldproxy/xtracfg:4.2.1 --version

# Konfiguration prüfen
docker run --rm -v ./ldproxy:/src ghcr.io/ldproxy/xtracfg:4.2.1 check

# Upgrade durchführen
docker run --rm -it -v ./ldproxy:/src ghcr.io/ldproxy/xtracfg:4.2.1 upgrade
