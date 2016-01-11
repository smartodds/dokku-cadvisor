# Dokku cAdvisor

[Google cAdvisor](https://github.com/google/cadvisor) plugin for [dokku](https://github.com/progrium/dokku)

Simple plugin that adds a `cadvisor` entry to the Dokku's menu to start/stop the service.

## Installation

On the Dokku server run the following:
```
sudo dokku plugin:install https://github.com/alessio/dokku-cadvisor
```

## Usage

```
Options:
    cadvisor, Show the status of cAdvisor
    cadvisor:start, Start Google cAdvisor service
    cadvisor:stop, Stop Google cAdvisor
```

## Notes

After the installation type the following to fire a ready-to-use container of Google cAdvisor:
```
dokku cadvisor:start
```
