# Redmine RTMaterial

## Summary

Add field "RTMaterial" for project.

You can selected color for RTMaterial Theme by project


## Installation

```
$ cd redmine/plugins
$ git clone https://github.com/fraoustin/redmine_rtmaterial.git
$ rake redmine:plugins:migrate NAME=redmine_rtmaterial
```

restart Redmine

for uninstall, you can use

```
$ cd redmine/plugins
$ rake redmine:plugins:migrate NAME=redmine_rtmaterial VERSION=0

```

restart Redmine