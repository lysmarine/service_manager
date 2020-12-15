# service_manager
service_manager is a component of lysmarine that is responsible to provide adapted service files for the binaries that need it. And a GUI interface to start/stop optional service 

## deployment
```
git clone --depth 1 https://github.com/lysmarine/service_manager/
debuild -S
dput ppa:lysmarine/lysmarine ../createap_*-ppa2_source.changes 
```

##local build
```
dpkg-buildpackage -rfakeroot -b -uc -us
```

This repository is distributed under GPLv3 
