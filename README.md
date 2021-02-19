# Portainer Templates for Selfhosted Projects/Homelabs
## Raspberry Pi 4 edition (Work In Progress)

This is a set of templates focused on helping people spin up selfhosted services using Portainer. Weather it is version 1 or 2 or even a custom list.

### Prerequisites

1. A Raspberry Pi 4 with docker installed
2. A Portainer setup.

*Want something we don't have? Make an issue and we'll work on adding it*

### Installing

1. Login to your portainer setup go to settings
2. Enable Use external templates
3. Add one of the following urls then go to app templates and hit refresh at the top:

`https://raw.githubusercontent.com/BuckeyeStudios/app-store/master/Portainer-v1/template.json`
`https://raw.githubusercontent.com/kingpinzs/app-store/master/Portainer-v2/template.json`
`https://raw.githubusercontent.com/BuckeyeStudios/app-store/master/Network-Monitor/template.json`

### Information
All templates are already configured to bind mount to various places on your drive. This branch works without the need for OMV. The following folders are all created in /portainer/

* **Files** - General file storage.
  * **AppData** - Subfolder where application data (unrelated to served data) is stored.
    * **Config** - Subfolder where configuration files for every container are stored.
* **Downloads** - Where bittorrent and usenet downloaders download files to.
* **TV** - Where tv shows are stored/moved to after downloaded.
* **Movies** - Where movies are stored/moved to after downloaded.
* **Music** - Where music is stored/moved to after downloaded.
* **Books** - Where books are stored/moved to after downloaded.
* **Comics** - Where comics are stored/moved to after downloaded.
* **Podcasts** - Where podcasts are stored/moved to after downloaded.

## App List

- Adguard
- Authelia
- Guacamole
- Homer
- Wikijs
- Bazarr
- Jellyfin
- Bitwarden_rs
- Pi-Hole
- Whoogle
- Mstream
- Filebrowser
- YouTubeDL-Material
- DashMachine
- Reactive-Resume
- LibreSpeed
- DeeMix
- Nginx Proxy Manager
- Organizrv2
- TiddlyWiki
- Watchtower
- transmission-openvpn
- airsonic
- beets
- booksonic
- bookstack
- calibre-web
- Chevereto
- codiad
- cops
- couchpotato
- daapd
- davos
- deluge
- domoticz
- duckdns
- duplicati
- freshrss
- gazee
- headphones
- heimdall
- htpcmanager
- jackett
- jellyfin (RASP4 Hardware acceleration)
- kodi-headless
- lazylibrarian
- letsencrypt / SWAG
- libresonic
- lidarr
- lychee
- mariadb
- mcmyadmin
- medusa
- minetest
- minisatip
- musicbrainz
- muximux
- mylar
- nextcloud
- nginx
- nzbget
- nzbhydra
- ombi
- openvpn-as
- oscam
- photoshow
- piwigo
- plex
- plexrequests
- projectsend
- pydio
- qbittorrent
- quassel-core
- radarr
- resilio-sync
- rutorrent
- sabnzbd
- sickchill
- smokeping
- sonarr
- syncthing
- tautulli
- thelounge
- transmission
- tt-rss
- tvheadend
- ubooquity
- unifi
- webgrabplus
- znc
- Yacht

## Contributing

If you wish to contribute make a pull request, create an issue, or email me.

## Authors
* **NASHosted** - *Current Work* - [NASHOSTED](https://github.com/nashosted)
* **SelfhostedPro** - *Current Work* - [SelfhostedPro](https://github.com/SelfhostedPro)
* **Jos Visser** - *Initial work* - [Qballjos](https://github.com/Qballjos)
* **xe-nvdk** - *template conversion to portainer V2* - [xe-nvdk](https://github.com/xe-nvdk)


## Acknowledgments

* LinuxServer.io for the old Template
* Inspiration being too lazy to create each container template manualy
* The team behind Portainer for there awesome product and support in the community
* https://github.com/Qballjos/portainer_templates the main git that this is based off of
