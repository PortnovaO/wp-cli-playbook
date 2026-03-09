# WP-CLI Playbook

## Basic Info
`wp --info` — shows WP-CLI environment information  
`wp help` — shows available commands  
`wp cli info` — shows CLI runtime info  

## Core
`wp core version` — shows WordPress version  
`wp core verify-checksums` — verifies WordPress core files  

## Plugins
`wp plugin list` — lists installed plugins  
`wp plugin activate plugin-name` — activates a plugin  
`wp plugin deactivate plugin-name` — deactivates a plugin  
`wp plugin update --all` — updates all plugins  

## Themes
`wp theme list` — lists installed themes  
`wp theme activate theme-name` — activates a theme  

## Users
`wp user list` — lists users  

## Database
`wp db export` — exports database  
`wp db import file.sql` — imports database  

## Options
`wp option get siteurl` — shows site URL  

## Cleanup / Cache
`wp transient delete --all` — deletes transients  
`wp cache flush` — flushes object cache
