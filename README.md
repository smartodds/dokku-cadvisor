# Dokku cAdvisor

[Google cAdvisor](https://github.com/google/cadvisor) plugin for [dokku](https://github.com/progrium/dokku)

Simple plugin that adds a `cadvisor` entry to the Dokku's menu to start/stop the service.

## Installation

On the Dokku server, install the plugin in the plugins directory and run `dokku plugins-install`:

```
cd /var/lib/dokku/plugins
git clone https://github.com/alessio/dokku-cadvisor cadvisor
dokku plugins-install
```

## Usage

```
Options:
    cadvisor:start              Start Google cAdvisor service
    cadvisor:stop               Stop Google cAdvisor
```

## Notes

After the installation type the following to fire a ready-to-use a container of Google cAdvisor:
```
dokku cadvisor:start
```
